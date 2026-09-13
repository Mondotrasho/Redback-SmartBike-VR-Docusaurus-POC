---
title: "Class PatrolPathGizmo"
sidebar_label: "PatrolPathGizmo"
---
# <a id="Platformer_PatrolPathGizmo"></a> Class PatrolPathGizmo

Namespace: [Platformer](Platformer.md)  
Assembly: DocFxProject.dll  

```csharp
[CustomEditor(typeof(PatrolPath))]
public class PatrolPathGizmo : Editor
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
Object ← 
ScriptableObject ← 
Editor ← 
[PatrolPathGizmo](Platformer.PatrolPathGizmo.md)

#### Inherited Members

Editor.SaveChanges\(\), 
Editor.DiscardChanges\(\), 
Editor.CreateEditorWithContext\(Object\[\], Object, Type\), 
Editor.CreateEditorWithContext\(Object\[\], Object\), 
Editor.CreateCachedEditorWithContext\(Object, Object, Type, ref Editor\), 
Editor.CreateCachedEditorWithContext\(Object\[\], Object, Type, ref Editor\), 
Editor.CreateCachedEditor\(Object, Type, ref Editor\), 
Editor.CreateCachedEditor\(Object\[\], Type, ref Editor\), 
Editor.CreateEditor\(Object\), 
Editor.CreateEditor\(Object, Type\), 
Editor.CreateEditor\(Object\[\]\), 
Editor.CreateEditor\(Object\[\], Type\), 
Editor.DrawPropertiesExcluding\(SerializedObject, params string\[\]\), 
Editor.DrawDefaultInspector\(\), 
Editor.Repaint\(\), 
Editor.OnInspectorGUI\(\), 
Editor.CreateInspectorGUI\(\), 
Editor.RequiresConstantRepaint\(\), 
Editor.DrawHeader\(\), 
Editor.OnHeaderGUI\(\), 
Editor.ShouldHideOpenButton\(\), 
Editor.DrawFoldoutInspector\(Object, ref Editor\), 
Editor.HasPreviewGUI\(\), 
Editor.GetPreviewTitle\(\), 
Editor.RenderStaticPreview\(string, Object\[\], int, int\), 
Editor.OnPreviewGUI\(Rect, GUIStyle\), 
Editor.OnInteractivePreviewGUI\(Rect, GUIStyle\), 
Editor.OnPreviewSettings\(\), 
Editor.GetInfoString\(\), 
Editor.DrawPreview\(Rect\), 
Editor.ReloadPreviewInstances\(\), 
Editor.UseDefaultMargins\(\), 
Editor.MoveNextTarget\(\), 
Editor.ResetTarget\(\), 
Editor.hasUnsavedChanges, 
Editor.saveChangesMessage, 
Editor.target, 
Editor.targets, 
Editor.serializedObject, 
Editor.finishedDefaultHeaderGUI, 
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

## Methods

### <a id="Platformer_PatrolPathGizmo_OnSceneGUI"></a> OnSceneGUI\(\)

```csharp
public void OnSceneGUI()
```

