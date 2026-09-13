---
title: "Class KinematicObject"
sidebar_label: "KinematicObject"
---
# <a id="Platformer_Mechanics_KinematicObject"></a> Class KinematicObject

Namespace: [Platformer.Mechanics](Platformer.Mechanics.md)  
Assembly: DocFxProject.dll  

Implements game physics for some in game entity.

```csharp
public class KinematicObject : MonoBehaviour
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
Object ← 
Component ← 
Behaviour ← 
MonoBehaviour ← 
[KinematicObject](Platformer.Mechanics.KinematicObject.md)

#### Derived

[AnimationController](Platformer.Mechanics.AnimationController.md), 
[PlayerController](Platformer.Mechanics.PlayerController.md)

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

### <a id="Platformer_Mechanics_KinematicObject_body"></a> body

```csharp
protected Rigidbody2D body
```

#### Field Value

 Rigidbody2D

### <a id="Platformer_Mechanics_KinematicObject_contactFilter"></a> contactFilter

```csharp
protected ContactFilter2D contactFilter
```

#### Field Value

 ContactFilter2D

### <a id="Platformer_Mechanics_KinematicObject_gravityModifier"></a> gravityModifier

A custom gravity coefficient applied to this entity.

```csharp
public float gravityModifier
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_Mechanics_KinematicObject_groundNormal"></a> groundNormal

```csharp
protected Vector2 groundNormal
```

#### Field Value

 Vector2

### <a id="Platformer_Mechanics_KinematicObject_hitBuffer"></a> hitBuffer

```csharp
protected RaycastHit2D[] hitBuffer
```

#### Field Value

 RaycastHit2D\[\]

### <a id="Platformer_Mechanics_KinematicObject_minGroundNormalY"></a> minGroundNormalY

The minimum normal (dot product) considered suitable for the entity sit on.

```csharp
public float minGroundNormalY
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_Mechanics_KinematicObject_minMoveDistance"></a> minMoveDistance

```csharp
protected const float minMoveDistance = 0.001
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_Mechanics_KinematicObject_shellRadius"></a> shellRadius

```csharp
protected const float shellRadius = 0.01
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_Mechanics_KinematicObject_targetVelocity"></a> targetVelocity

```csharp
protected Vector2 targetVelocity
```

#### Field Value

 Vector2

### <a id="Platformer_Mechanics_KinematicObject_velocity"></a> velocity

The current velocity of the entity.

```csharp
public Vector2 velocity
```

#### Field Value

 Vector2

## Properties

### <a id="Platformer_Mechanics_KinematicObject_IsGrounded"></a> IsGrounded

Is the entity currently sitting on a surface?

```csharp
public bool IsGrounded { get; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="Platformer_Mechanics_KinematicObject_Bounce_System_Single_"></a> Bounce\(float\)

Bounce the object's vertical velocity.

```csharp
public void Bounce(float value)
```

#### Parameters

`value` [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_Mechanics_KinematicObject_Bounce_UnityEngine_Vector2_"></a> Bounce\(Vector2\)

Bounce the objects velocity in a direction.

```csharp
public void Bounce(Vector2 dir)
```

#### Parameters

`dir` Vector2

### <a id="Platformer_Mechanics_KinematicObject_ComputeVelocity"></a> ComputeVelocity\(\)

```csharp
protected virtual void ComputeVelocity()
```

### <a id="Platformer_Mechanics_KinematicObject_FixedUpdate"></a> FixedUpdate\(\)

```csharp
protected virtual void FixedUpdate()
```

### <a id="Platformer_Mechanics_KinematicObject_OnDisable"></a> OnDisable\(\)

```csharp
protected virtual void OnDisable()
```

### <a id="Platformer_Mechanics_KinematicObject_OnEnable"></a> OnEnable\(\)

```csharp
protected virtual void OnEnable()
```

### <a id="Platformer_Mechanics_KinematicObject_Start"></a> Start\(\)

```csharp
protected virtual void Start()
```

### <a id="Platformer_Mechanics_KinematicObject_Teleport_UnityEngine_Vector3_"></a> Teleport\(Vector3\)

Teleport to some position.

```csharp
public void Teleport(Vector3 position)
```

#### Parameters

`position` Vector3

### <a id="Platformer_Mechanics_KinematicObject_Update"></a> Update\(\)

```csharp
protected virtual void Update()
```

