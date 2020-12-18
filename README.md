# OutscalBasicUnity

using System.Unity.Collections;
using System.Unity.Collections;
using UnityEngine;

public class MyFirstScript : Monobehaviour
{

	void Awake()
	{
	debug.log ("MyFirstScript Awake function");
	}

	void Start()
	{
	debug.log ("MyFirstScript Start function");
	}

	void Update()
		if(Input.GetKeyDown(KeyCode.F) || Input.GetMousebuttonDown(0));
	{
	debug.log("Update Input F pressed");
	}
		
		if(Input.GetKeyUp(KeyCode.F) || Input.GetMouseButtonUp(0));
	

	{
	debug.log("Update Input F released");
	}
		
		if(Input.GetKey(KeyCode. F));

	{
	debug.log("Update Input F");
	}
	
	private void Lateupdate()
	{
	debug.log("MyFirstScript Lateupdate function");
	}

	private void Ondestroy()
	{
	debug.log("MyFirstScript Ondestroy function")
	}

}
