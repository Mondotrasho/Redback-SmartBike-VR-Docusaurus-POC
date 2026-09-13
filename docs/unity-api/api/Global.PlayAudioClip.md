---
title: "Class PlayAudioClip"
sidebar_label: "PlayAudioClip"
---
# <a id="Global_PlayAudioClip"></a> Class PlayAudioClip

Namespace:   
Assembly: DocFxProject.dll  

This class allows an audio clip to be played during an animation state.

```csharp
public class PlayAudioClip : StateMachineBehaviour
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
Object ← 
ScriptableObject ← 
StateMachineBehaviour ← 
[PlayAudioClip](PlayAudioClip.md)

#### Inherited Members

StateMachineBehaviour.OnStateEnter\(Animator, AnimatorStateInfo, int\), 
StateMachineBehaviour.OnStateUpdate\(Animator, AnimatorStateInfo, int\), 
StateMachineBehaviour.OnStateExit\(Animator, AnimatorStateInfo, int\), 
StateMachineBehaviour.OnStateMove\(Animator, AnimatorStateInfo, int\), 
StateMachineBehaviour.OnStateIK\(Animator, AnimatorStateInfo, int\), 
StateMachineBehaviour.OnStateMachineEnter\(Animator, int\), 
StateMachineBehaviour.OnStateMachineExit\(Animator, int\), 
StateMachineBehaviour.OnStateEnter\(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable\), 
StateMachineBehaviour.OnStateUpdate\(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable\), 
StateMachineBehaviour.OnStateExit\(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable\), 
StateMachineBehaviour.OnStateMove\(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable\), 
StateMachineBehaviour.OnStateIK\(Animator, AnimatorStateInfo, int, AnimatorControllerPlayable\), 
StateMachineBehaviour.OnStateMachineEnter\(Animator, int, AnimatorControllerPlayable\), 
StateMachineBehaviour.OnStateMachineExit\(Animator, int, AnimatorControllerPlayable\), 
ScriptableObject.SetDirty\(\), 
ScriptableObject.CreateInstance\(string\), 
ScriptableObject.CreateInstance\(Type\), 
ScriptableObject.CreateInstance<T\>\(\), 
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

### <a id="Global_PlayAudioClip_clip"></a> clip

The audio clip to be played.

```csharp
public AudioClip clip
```

#### Field Value

 AudioClip

### <a id="Global_PlayAudioClip_modulus"></a> modulus

If greater than zero, the normalized time will be (normalizedTime % modulus).
This is used to repeat the audio clip when the animation state loops.

```csharp
public float modulus
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Global_PlayAudioClip_t"></a> t

The point in normalized time where the clip should play.

```csharp
public float t
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

## Methods

### <a id="Global_PlayAudioClip_OnStateUpdate_UnityEngine_Animator_UnityEngine_AnimatorStateInfo_System_Int32_"></a> OnStateUpdate\(Animator, AnimatorStateInfo, int\)

```csharp
public override void OnStateUpdate(Animator animator, AnimatorStateInfo stateInfo, int layerIndex)
```

#### Parameters

`animator` Animator

`stateInfo` AnimatorStateInfo

`layerIndex` [int](https://learn.microsoft.com/dotnet/api/system.int32)

