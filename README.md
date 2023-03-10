# myBabylon

### 1단계 : Your Journey Starts Here

https://doc.babylonjs.com/journey/theFirstStep 

### 2단계 : Features - Starter Scene Code

https://doc.babylonjs.com/features/starterSceneCode

### 3단계 : Features - Introduction - Firsts

https://doc.babylonjs.com/features/introductionToFeatures/chap1


### 4단계 : Features - Deep Dive - Cameras - Camera Introduction (Arc Rotate Camera) 

https://doc.babylonjs.com/features/featuresDeepDive/cameras/camera_introduction (카메라 설정)

예시 : const camera = new BABYLON.ArcRotateCamera("camera", -Math.PI / 2, Math.PI / 2.5, 10, new BABYLON.Vector3(0, 0, 0));

-Math.PI / 2  : 알파값(세로 방향 회전, radian 단위, 반시계 방향)

Math.PI / 2.5 : 베타값(위도 방향 회전, radian 단위)

10            : 반경  (목표물로부터의 거리) 


### 5단계 : Tools and Resources - Utility Functions - Display Axes

https://playground.babylonjs.com/#T8UQTA (X/Y/Z 축에 대한 이해)

* Axes Viewer

X축 : red, Y축 : green, Z축 : Blue

예시 : const localAxes = new BABYLON.AxesViewer(scene, 1);  // 축의 길이를 1로 설정


### 6단계 : Features - Deep Dive - Mesh - Creating Meshes - Create Set Shapes (기본 도형 만들기)

https://doc.babylonjs.com/features/featuresDeepDive/mesh/creation/set

실습예제 : https://playground.babylonjs.com/#6XIT28#3455 (Meshes)

* plane : yz평면 기준, ground : xz평면 기준, tessellation : 도형을 만드는 옆면(?)의 갯수


### 7단계 : Features - Deep Dive - Mesh - Creating Meshes - Create Parametric Meshes 

https://doc.babylonjs.com/features/featuresDeepDive/mesh/creation/param

실습예제 : https://playground.babylonjs.com/#6XIT28#3459  (lines)

실습예제 : https://playground.babylonjs.com/#6XIT28#3460  (dashed lines) 

* 대시와 간격의 실제 길이는 dashNb 에 의해 설정된 개수 와 실제 크기가 아닌 dashSize 와 * gapSize* 의 비율 에 따라 결정

실습예제 : https://playground.babylonjs.com/#DKAFIL (화살표 만들기)

### 8단계 : 3D 도형 연습

실습예제 : https://playground.babylonjs.com/#7TDWAE#1 (40 x 40개의 random 실린더를 생성하고, random값에 따라 높이와 색상 부여)





