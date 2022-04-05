# ProjectGKV based with C++
Project Transformasi 3D pada objek Kubus dengan menggunakan C++ dan OpenGL pada IDE Dev Cpp
<br> Jenis transformasi dasar yang digunakan ialah :
## Translasi
```cpp
glTranslatef(1.0f,2.0f,3.0f); 
// translasi dengan nilai/parameter x=1, y=2, dan z=3
```
## Skala
```cpp
glScalef(2.0f,2.0f,2.0f); 
// overall scaling dengan faktor skala 2
```
## Rotasi
```cpp
glRotatef(180,0.0f,0.0f,1.0f); 
// rotasi 180 derajat pada sumbu z
```

## Keyboard function
Untuk menerima masukan keyboard left,right,up, and down agar program dapat diubah arah pandangnya
```cpp
void pressKey(int key, int x, int y) { 
 // Fungsi ini akan dijalankan saat tombol keyboard ditekan dan 
 // Selama tombol ditekan, variabel angle dan move diubah => kamera 
 switch (key) { 
 case GLUT_KEY_LEFT : deltaAngle = -0.01f;break; 
 case GLUT_KEY_RIGHT : deltaAngle = 0.01f;break; 
 case GLUT_KEY_UP : deltaMove = 1;break; 
 case GLUT_KEY_DOWN : deltaMove = -1;break; 
 } 
 ```
 
 
