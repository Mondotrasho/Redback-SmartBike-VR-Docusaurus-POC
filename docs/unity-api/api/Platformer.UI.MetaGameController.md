---
title: "Class MetaGameController"
sidebar_label: "MetaGameController"
---
# <a id="Platformer_UI_MetaGameController"></a> Class MetaGameController

Namespace: [Platformer.UI](Platformer.UI.md)  
Assembly: DocFxProject.dll  

The MetaGameController is responsible for switching control between the high level
contexts of the application, eg the Main Menu and Gameplay systems.

```csharp
public class MetaGameController : MonoBehaviour
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
Object ← 
Component ← 
Behaviour ← 
MonoBehaviour ← 
[MetaGameController](Platformer.UI.MetaGameController.md)

#### Inherited Members

MonoBehaviour.IsInvoking\(\), 
MonoBehaviour.CancelInvoke\(\), 
MonoBehaviour.Invoke\(string, float\), 
MonoBehaviour.InvokeRepeating\(string, float, float\), 
MonoBehaviour.CancelInvoke\(string\), 
MonoBehaviour.IsInvoking\(string\), 
MonoBehaviour.StartCoroutine\(string\), 
MonoBehaviour.StartCoroutine\(string, object\), 
MonoBehaviour.StartCoroutine\(IEnumerator\), 
MonoBehaviour.StartCoroutine\_Auto\(IEnumerator\), 
MonoBehaviour.StopCoroutine\(IEnumerator\), 
MonoBehaviour.StopCoroutine\(Coroutine\), 
MonoBehaviour.StopCoroutine\(string\), 
MonoBehaviour.StopAllCoroutines\(\), 
MonoBehaviour.print\(object\), 
MonoBehaviour.destroyCancellationToken, 
MonoBehaviour.useGUILayout, 
MonoBehaviour.runInEditMode, 
Behaviour.enabled, 
Behaviour.isActiveAndEnabled, 
Component.GetComponent\(Type\), 
Component.GetComponent<T\>\(\), 
Component.TryGetComponent\(Type, out Component\), 
Component.TryGetComponent<T\>\(out T\), 
Component.GetComponent\(string\), 
Component.GetComponentInChildren\(Type, bool\), 
Component.GetComponentInChildren\(Type\), 
Component.GetComponentInChildren<T\>\(bool\), 
Component.GetComponentInChildren<T\>\(\), 
Component.GetComponentsInChildren\(Type, bool\), 
Component.GetComponentsInChildren\(Type\), 
Component.GetComponentsInChildren<T\>\(bool\), 
Component.GetComponentsInChildren<T\>\(bool, List<T\>\), 
Component.GetComponentsInChildren<T\>\(\), 
Component.GetComponentsInChildren<T\>\(List<T\>\), 
Component.GetComponentInParent\(Type, bool\), 
Component.GetComponentInParent\(Type\), 
Component.GetComponentInParent<T\>\(bool\), 
Component.GetComponentInParent<T\>\(\), 
Component.GetComponentsInParent\(Type, bool\), 
Component.GetComponentsInParent\(Type\), 
Component.GetComponentsInParent<T\>\(bool\), 
Component.GetComponentsInParent<T\>\(bool, List<T\>\), 
Component.GetComponentsInParent<T\>\(\), 
Component.GetComponents\(Type\), 
Component.GetComponents\(Type, List<Component\>\), 
Component.GetComponents<T\>\(List<T\>\), 
Component.GetComponents<T\>\(\), 
Component.GetComponentIndex\(\), 
Component.CompareTag\(string\), 
Component.SendMessageUpwards\(string, object, SendMessageOptions\), 
Component.SendMessageUpwards\(string, object\), 
Component.SendMessageUpwards\(string\), 
Component.SendMessageUpwards\(string, SendMessageOptions\), 
Component.SendMessage\(string, object\), 
Component.SendMessage\(string\), 
Component.SendMessage\(string, object, SendMessageOptions\), 
Component.SendMessage\(string, SendMessageOptions\), 
Component.BroadcastMessage\(string, object, SendMessageOptions\), 
Component.BroadcastMessage\(string, object\), 
Component.BroadcastMessage\(string\), 
Component.BroadcastMessage\(string, SendMessageOptions\), 
Component.transform, 
Component.gameObject, 
Component.tag, 
Object.GetInstanceID\(\), 
Object.GetHashCode\(\), 
Object.Equals\(object\), 
Object.InstantiateAsync<T\>\(T\), 
Object.InstantiateAsync<T\>\(T, Transform\), 
Object.InstantiateAsync<T\>\(T, Vector3, Quaternion\), 
Object.InstantiateAsync<T\>\(T, Transform, Vector3, Quaternion\), 
Object.InstantiateAsync<T\>\(T, int\), 
Object.InstantiateAsync<T\>\(T, int, Transform\), 
Object.InstantiateAsync<T\>\(T, int, Vector3, Quaternion\), 
Object.InstantiateAsync<T\>\(T, int, ReadOnlySpan<Vector3\>, ReadOnlySpan<Quaternion\>\), 
Object.InstantiateAsync<T\>\(T, int, Transform, Vector3, Quaternion\), 
Object.InstantiateAsync<T\>\(T, int, Transform, ReadOnlySpan<Vector3\>, ReadOnlySpan<Quaternion\>\), 
Object.Instantiate\(Object, Vector3, Quaternion\), 
Object.Instantiate\(Object, Vector3, Quaternion, Transform\), 
Object.Instantiate\(Object\), 
Object.Instantiate\(Object, Scene\), 
Object.Instantiate\(Object, Transform\), 
Object.Instantiate\(Object, Transform, bool\), 
Object.Instantiate<T\>\(T\), 
Object.Instantiate<T\>\(T, Vector3, Quaternion\), 
Object.Instantiate<T\>\(T, Vector3, Quaternion, Transform\), 
Object.Instantiate<T\>\(T, Transform\), 
Object.Instantiate<T\>\(T, Transform, bool\), 
Object.Destroy\(Object, float\), 
Object.Destroy\(Object\), 
Object.DestroyImmediate\(Object, bool\), 
Object.DestroyImmediate\(Object\), 
Object.FindObjectsOfType\(Type\), 
Object.FindObjectsOfType\(Type, bool\), 
Object.FindObjectsByType\(Type, FindObjectsSortMode\), 
Object.FindObjectsByType\(Type, FindObjectsInactive, FindObjectsSortMode\), 
Object.DontDestroyOnLoad\(Object\), 
Object.DestroyObject\(Object, float\), 
Object.DestroyObject\(Object\), 
Object.FindSceneObjectsOfType\(Type\), 
Object.FindObjectsOfTypeIncludingAssets\(Type\), 
Object.FindObjectsOfType<T\>\(\), 
Object.FindObjectsByType<T\>\(FindObjectsSortMode\), 
Object.FindObjectsOfType<T\>\(bool\), 
Object.FindObjectsByType<T\>\(FindObjectsInactive, FindObjectsSortMode\), 
Object.FindObjectOfType<T\>\(\), 
Object.FindObjectOfType<T\>\(bool\), 
Object.FindFirstObjectByType<T\>\(\), 
Object.FindAnyObjectByType<T\>\(\), 
Object.FindFirstObjectByType<T\>\(FindObjectsInactive\), 
Object.FindAnyObjectByType<T\>\(FindObjectsInactive\), 
Object.FindObjectsOfTypeAll\(Type\), 
Object.FindObjectOfType\(Type\), 
Object.FindFirstObjectByType\(Type\), 
Object.FindAnyObjectByType\(Type\), 
Object.FindObjectOfType\(Type, bool\), 
Object.FindFirstObjectByType\(Type, FindObjectsInactive\), 
Object.FindAnyObjectByType\(Type, FindObjectsInactive\), 
Object.ToString\(\), 
Object.name, 
Object.hideFlags, 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Fields

### <a id="Platformer_UI_MetaGameController_gameController"></a> gameController

The game controller.

```csharp
public GameController gameController
```

#### Field Value

 [GameController](Platformer.Mechanics.GameController.md)

### <a id="Platformer_UI_MetaGameController_gamePlayCanvasii"></a> gamePlayCanvasii

A list of canvas objects which are used during gameplay (when the main ui is turned off)

```csharp
public Canvas[] gamePlayCanvasii
```

#### Field Value

 Canvas\[\]

### <a id="Platformer_UI_MetaGameController_mainMenu"></a> mainMenu

The main UI object which used for the menu.

```csharp
public MainUIController mainMenu
```

#### Field Value

 [MainUIController](Platformer.UI.MainUIController.md)

## Methods

### <a id="Platformer_UI_MetaGameController_ToggleMainMenu_System_Boolean_"></a> ToggleMainMenu\(bool\)

Turn the main menu on or off.

```csharp
public void ToggleMainMenu(bool show)
```

#### Parameters

`show` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

