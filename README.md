# KPoolManager
Object pooling for unity games. Have a reference to the pool manager in the scene and use .Clone(Prefab Transform) for cloning and use .Free(Transform) for freeing clones. More juicy documentation will be released later. I developed this on top of 2020.3.3f1 but I believe you can use version!

#### Installation:
* Add an entry in your manifest.json as follows:
```C#
"com.kaiyum.kpoolmanager": "https://github.com/kaiyumcg/KPoolManager.git"
```


Since unity does not support git dependencies, you need the following entries as well:
```C#
"com.kaiyum.attributeext2": "https://github.com/kaiyumcg/NaughtyAttributes",
"com.kaiyum.unityext": "https://github.com/kaiyumcg/UnityExt.git",
"com.kaiyum.editorutil": "https://github.com/kaiyumcg/EditorUtil.git"
```
Add them into your manifest.json file in "Packages\" directory of your unity project, if they are already not in manifest.json file.
