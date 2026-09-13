---
title: "Class PlayerController"
sidebar_label: "PlayerController"
---
# <a id="Platformer_Mechanics_PlayerController"></a> Class PlayerController

Namespace: [Platformer.Mechanics](Platformer.Mechanics.md)  
Assembly: DocFxProject.dll  

This is the main class used to implement control of the player.
It is a superset of the AnimationController class, but is inlined to allow for any kind of customisation.

```csharp
public class PlayerController : KinematicObject
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
Object ← 
Component ← 
Behaviour ← 
MonoBehaviour ← 
[KinematicObject](Platformer.Mechanics.KinematicObject.md) ← 
[PlayerController](Platformer.Mechanics.PlayerController.md)

#### Inherited Members

[KinematicObject.minGroundNormalY](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_minGroundNormalY), 
[KinematicObject.gravityModifier](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_gravityModifier), 
[KinematicObject.velocity](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_velocity), 
[KinematicObject.IsGrounded](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_IsGrounded), 
[KinematicObject.targetVelocity](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_targetVelocity), 
[KinematicObject.groundNormal](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_groundNormal), 
[KinematicObject.body](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_body), 
[KinematicObject.contactFilter](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_contactFilter), 
[KinematicObject.hitBuffer](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_hitBuffer), 
[KinematicObject.minMoveDistance](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_minMoveDistance), 
[KinematicObject.shellRadius](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_shellRadius), 
[KinematicObject.Bounce\(float\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_Bounce\_System\_Single\_), 
[KinematicObject.Bounce\(Vector2\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_Bounce\_UnityEngine\_Vector2\_), 
[KinematicObject.Teleport\(Vector3\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_Teleport\_UnityEngine\_Vector3\_), 
[KinematicObject.OnEnable\(\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_OnEnable), 
[KinematicObject.OnDisable\(\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_OnDisable), 
[KinematicObject.Start\(\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_Start), 
[KinematicObject.Update\(\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_Update), 
[KinematicObject.ComputeVelocity\(\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_ComputeVelocity), 
[KinematicObject.FixedUpdate\(\)](Platformer.Mechanics.KinematicObject.md\#Platformer\_Mechanics\_KinematicObject\_FixedUpdate), 
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

### <a id="Platformer_Mechanics_PlayerController_audioSource"></a> audioSource

```csharp
public AudioSource audioSource
```

#### Field Value

 AudioSource

### <a id="Platformer_Mechanics_PlayerController_collider2d"></a> collider2d

```csharp
public Collider2D collider2d
```

#### Field Value

 Collider2D

### <a id="Platformer_Mechanics_PlayerController_controlEnabled"></a> controlEnabled

```csharp
public bool controlEnabled
```

#### Field Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="Platformer_Mechanics_PlayerController_health"></a> health

```csharp
public Health health
```

#### Field Value

 [Health](Platformer.Mechanics.Health.md)

### <a id="Platformer_Mechanics_PlayerController_jumpAudio"></a> jumpAudio

```csharp
public AudioClip jumpAudio
```

#### Field Value

 AudioClip

### <a id="Platformer_Mechanics_PlayerController_jumpState"></a> jumpState

```csharp
public PlayerController.JumpState jumpState
```

#### Field Value

 [PlayerController](Platformer.Mechanics.PlayerController.md).[JumpState](Platformer.Mechanics.PlayerController.JumpState.md)

### <a id="Platformer_Mechanics_PlayerController_jumpTakeOffSpeed"></a> jumpTakeOffSpeed

Initial jump velocity at the start of a jump.

```csharp
public float jumpTakeOffSpeed
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_Mechanics_PlayerController_maxSpeed"></a> maxSpeed

Max horizontal speed of the player.

```csharp
public float maxSpeed
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_Mechanics_PlayerController_ouchAudio"></a> ouchAudio

```csharp
public AudioClip ouchAudio
```

#### Field Value

 AudioClip

### <a id="Platformer_Mechanics_PlayerController_respawnAudio"></a> respawnAudio

```csharp
public AudioClip respawnAudio
```

#### Field Value

 AudioClip

## Properties

### <a id="Platformer_Mechanics_PlayerController_Bounds"></a> Bounds

```csharp
public Bounds Bounds { get; }
```

#### Property Value

 Bounds

## Methods

### <a id="Platformer_Mechanics_PlayerController_ComputeVelocity"></a> ComputeVelocity\(\)

```csharp
protected override void ComputeVelocity()
```

### <a id="Platformer_Mechanics_PlayerController_Update"></a> Update\(\)

```csharp
protected override void Update()
```

