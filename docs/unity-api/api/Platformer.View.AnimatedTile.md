---
title: "Class AnimatedTile"
sidebar_label: "AnimatedTile"
---
# <a id="Platformer_View_AnimatedTile"></a> Class AnimatedTile

Namespace: [Platformer.View](Platformer.View.md)  
Assembly: DocFxProject.dll  

```csharp
[Serializable]
[CreateAssetMenu(fileName = "New Animated Tile", menuName = "Tiles/Animated Tile")]
public class AnimatedTile : TileBase
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
Object ← 
ScriptableObject ← 
TileBase ← 
[AnimatedTile](Platformer.View.AnimatedTile.md)

#### Inherited Members

TileBase.RefreshTile\(Vector3Int, ITilemap\), 
TileBase.GetTileData\(Vector3Int, ITilemap, ref TileData\), 
TileBase.GetTileAnimationData\(Vector3Int, ITilemap, ref TileAnimationData\), 
TileBase.StartUp\(Vector3Int, ITilemap, GameObject\), 
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

### <a id="Platformer_View_AnimatedTile_m_AnimatedSprites"></a> m\_AnimatedSprites

```csharp
public Sprite[] m_AnimatedSprites
```

#### Field Value

 Sprite\[\]

### <a id="Platformer_View_AnimatedTile_m_AnimationStartTime"></a> m\_AnimationStartTime

```csharp
public float m_AnimationStartTime
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_View_AnimatedTile_m_MaxSpeed"></a> m\_MaxSpeed

```csharp
public float m_MaxSpeed
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_View_AnimatedTile_m_MinSpeed"></a> m\_MinSpeed

```csharp
public float m_MinSpeed
```

#### Field Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="Platformer_View_AnimatedTile_m_TileColliderType"></a> m\_TileColliderType

```csharp
public Tile.ColliderType m_TileColliderType
```

#### Field Value

 Tile.ColliderType

## Methods

### <a id="Platformer_View_AnimatedTile_GetTileAnimationData_UnityEngine_Vector3Int_UnityEngine_Tilemaps_ITilemap_UnityEngine_Tilemaps_TileAnimationData__"></a> GetTileAnimationData\(Vector3Int, ITilemap, ref TileAnimationData\)

```csharp
public override bool GetTileAnimationData(Vector3Int location, ITilemap tileMap, ref TileAnimationData tileAnimationData)
```

#### Parameters

`location` Vector3Int

`tileMap` ITilemap

`tileAnimationData` TileAnimationData

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="Platformer_View_AnimatedTile_GetTileData_UnityEngine_Vector3Int_UnityEngine_Tilemaps_ITilemap_UnityEngine_Tilemaps_TileData__"></a> GetTileData\(Vector3Int, ITilemap, ref TileData\)

```csharp
public override void GetTileData(Vector3Int location, ITilemap tileMap, ref TileData tileData)
```

#### Parameters

`location` Vector3Int

`tileMap` ITilemap

`tileData` TileData

