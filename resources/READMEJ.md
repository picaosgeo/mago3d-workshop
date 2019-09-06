# Workshop Data
## サンプルデータおよび変換結果資料
| 項目 | 内容 |
| ---------- | ---------- |
| data/raw/SangJiUniversity/dae.zip | raw dae サンプル資料（尚志） |
| data/raw/SangJiUniversity/las.zip | raw las サンプル資料（尚志） |
| data/f4d/SangJiUniversity/dae.zip | f4d dae サンプル資料（尚志） |
| data/f4d/SangJiUniversity/las.zip | f4d las サンプル資料（尚志） |
| data/f4d/SangJiUniversity/workshop-data-collada.json | f4d dae 変換材料について |
| data/f4d/SangJiUniversity/workshop-data-pointcloud.json | f4d dae 変換材料について |

# サンプル資料を変換するためのコマンド
## Workshop Data for Collada
- .dae(Collda) ファイル変換時の変換係数
```
F4DConverter #inputFolder [変換元のCOLLADAファイルを含むフォルダ] #outputFolder [F4Dの保存されるフォルダ] #meshType 1 #log [ログファイルのフルパス] #epsg 5186 #offsetX 282345 #offsetY 530506 #idPrefix DAE_ #isYAxisUp y #indexing y
```

## Workshop Data for PointCloud
- .las(PointCloud) ファイル変換時の変換係数

```
F4DConverter #inputFolder [変換元のlasファイルを含むフォルダ] #outputFolder [F4Dの保存されるフォルダ] #meshType 3 #log [ログファイルのフルパス] #indexing y
```

# mago3D
| 項目 | 内容 |
| ---------- | ---------- |
| mago3d-js |  |
| mago3d-converter |  |
| mago3d-cms |  |

## mago3D.JS
## mago3D Converter
## mago3D CMS
