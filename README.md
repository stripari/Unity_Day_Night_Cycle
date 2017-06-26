# Unity_Day_Night_Cycle
Code chunk for creating a day to night cycle within unity

using UnityEngine;
using System.Collections;

public class DayNightCycle : MonoBehaviour {

	// Use this for initialization
	void Start () {
	
	}
	
	// Update is called once per frame
	void Update () {
		this.transform.Rotate (new Vector3 (3f * Time.deltaTime, 0f, 0f));
	}
}
