# Workshop Data
## 샘플자료 및 변환 결과자료
| 항목 | 내용 |
| ---------- | ---------- |
| data/raw/SangJiUniversity/dae.zip | raw dae 샘플자료(상지대) |
| data/raw/SangJiUniversity/las.zip | raw las 샘플자료(상지대) |
| data/f4d/SangJiUniversity/dae.zip | f4d dae 변환자료(상지대) |
| data/f4d/SangJiUniversity/las.zip | f4d las 변환자료(상지대) |
| data/f4d/SangJiUniversity/workshop-data-collada.json | f4d dae 변환자료 정보 |
| data/f4d/SangJiUniversity/workshop-data-pointcloud.json | f4d dae 변환자료 정보 |

# 샘플자료를 변환하기 위한 명령어
## Workshop Data for Collada
- .dae(Collda) 파일 변환 시 변환기 인자
```
F4DConverter #inputFolder [원본COLLADA파일들어있는폴더] #outputFolder [F4D저장되는폴더] #meshType 1 #log [로그파일전체경로] #epsg 5186 #offsetX 282345 #offsetY 530506 #idPrefix DAE_ #isYAxisUp y #indexing y
```

## Workshop Data for PointCloud
- .las(PointCloud) 파일 변환 시 변환기 인자

```
F4DConverter #inputFolder [원본las파일들어있는폴더] #outputFolder [F4D저장되는폴더] #meshType 3 #log [로그파일전체경로] #indexing y
```

# mago3D
| 항목 | 내용 |
| ---------- | ---------- |
| mago3d-js |  |
| mago3d-converter |  |
| mago3d-cms |  |

## mago3D.JS
## mago3D Converter
## mago3D CMS