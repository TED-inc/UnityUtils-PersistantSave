# UnityUtils-PersistantSave
Require:
- TED-inc/UnityUtils-Encryption
- TED-inc/UnityUtils-MathExt
- TED-inc/UnityUtils-Components

Using:
1) Add "PersistantSaveInstance" component to DontDestoyOnLoad
2) Invoke "Randomize Encryption" on this component
3) Create scriptable object which you want to save in persistant
4) Add it to "PersistantSaveInstance".
	If you have methods marked with attribute "PersistantSaveInvokeOnLoad", it will call them