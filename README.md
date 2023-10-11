# UnityAutomatedTestingDemo

This is a simple demo to toy with the Unity Test Framework (UTF) provided by Unity. The demo uses the third person character controller package provided by the Unity asset store; the package contains a scene with a controllable character. The tutorial for this demo is provided by Unity which can be found here https://unity.com/how-to/automated-tests-unity-test-framework.

The UTF supports two categories of tests: edit mode and play mode. Play mode lets you exercise game code at runtime and is the method used in this demo. 

# Writing and Executing a Test Case
After setting up the UTF and any necessary assembly definitions, tests can be created like normal scripts. The difference is that you use attributes to mark methods as tests. After creating a method and marking it as a test with the attribute, it can be executed through the GUI with the Test Runnner window.
