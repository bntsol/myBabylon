# myBabylon

### Step1 : Your Journey Starts Here

https://doc.babylonjs.com/journey/theFirstStep 

### Step 2 : Features - Starter Scene Code

https://doc.babylonjs.com/features/starterSceneCode

### Step 3 : Features - Introduction - Firsts

https://doc.babylonjs.com/features/introductionToFeatures/chap1


### Step 4 : Features - Deep Dive - Cameras - Camera Introduction (Arc Rotate Camera) 

https://doc.babylonjs.com/features/featuresDeepDive/cameras/camera_introduction (카메라 설정)

예시 : const camera = new BABYLON.ArcRotateCamera("camera", -Math.PI / 2, Math.PI / 2.5, 10, new BABYLON.Vector3(0, 0, 0));

-Math.PI / 2  : 알파값(세로 방향 회전, radian 단위, 반시계 방향)

Math.PI / 2.5 : 베타값(위도 방향 회전, radian 단위)

10            : 반경  (목표물로부터의 거리) 


### Step 5 : Tools and Resources - Utility Functions - Display Axes

https://playground.babylonjs.com/#T8UQTA (X/Y/Z 축에 대한 이해)

* Axes Viewer

X축 : red, Y축 : green, Z축 : Blue

예시 : const localAxes = new BABYLON.AxesViewer(scene, 1);  // 축의 길이를 1로 설정


### Step 6 : Features - Deep Dive - Mesh - Creating Meshes - Create Set Shapes (기본 도형 만들기)

https://doc.babylonjs.com/features/featuresDeepDive/mesh/creation/set

실습예제 : https://playground.babylonjs.com/#6XIT28#3455 (Meshes)

* plane : yz평면 기준, ground : xz평면 기준, tessellation : 도형을 만드는 옆면(?)의 갯수


### Step 7 : Features - Deep Dive - Mesh - Creating Meshes - Create Parametric Meshes 

https://doc.babylonjs.com/features/featuresDeepDive/mesh/creation/param

실습예제 : https://playground.babylonjs.com/#6XIT28#3459  (lines)

실습예제 : https://playground.babylonjs.com/#6XIT28#3460  (dashed lines) 

* 대시와 간격의 실제 길이는 dashNb 에 의해 설정된 개수 와 실제 크기가 아닌 dashSize 와 * gapSize* 의 비율 에 따라 결정

실습예제 : https://playground.babylonjs.com/#DKAFIL (화살표 만들기)

### Step 8 : 3D 도형 연습

실습예제 : https://playground.babylonjs.com/#7TDWAE#1 (40 x 40개의 random 실린더를 생성하고, random값에 따라 높이와 색상 부여)

### Further Study

Step 9 : Creating A Tiled Ground : https://doc.babylonjs.com/features/featuresDeepDive/mesh/creation/set/tiled_ground

Step 10 : Meshing Transformations : https://doc.babylonjs.com/features/featuresDeepDive/mesh/transforms

Step 11 : Levels of Detail (LOD) : https://doc.babylonjs.com/features/featuresDeepDive/mesh/LOD

Step 12 : Simplifying Meshes With Auto-LOD : https://doc.babylonjs.com/features/featuresDeepDive/mesh/simplifyingMeshes

Step 13 : Trail Mesh : https://doc.babylonjs.com/features/featuresDeepDive/mesh/trailMesh

Step 14 : Dynamic Terrain : https://doc.babylonjs.com/communityExtensions/dynamicTerrains

Step 15 : Quad Tree


