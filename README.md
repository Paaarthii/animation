# Ex.No: 6 Develop a application to add animations to ImageView,Move,blink,fade,clockwise,zoom,slide operations are perform in android studio.

## AIM:

To develop a application to add animation to imageview,move,blink,fade,clockwise,zoom,slide operation using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Latest Version)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Design the layout using activity_main.xml

Step 3: Add an ImageView to display the image and add buttons for each animation (Move, Blink, Fade, Clockwise, Zoom, Slide).

Step 4: Import the image into the drawable folder.

Step 5: Create animation XML files under res/anim/ for each animation type such as blink, fade, move, rotate, slide and zoom.

Step 6: Type the Java program in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Developed by: PARTHIPAN M
Registeration Number : 212225040294
*/
```
## Activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:orientation="vertical"
    android:gravity="center"
    android:padding="20dp"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/imageView"
        android:src="@mipmap/ic_launcher"
        android:layout_width="150dp"
        android:layout_height="150dp"
        android:layout_marginBottom="20dp" />

    <Button
        android:id="@+id/blinkBtn"
        android:text="Blink Animation"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />

    <Button
        android:id="@+id/rotateBtn"
        android:text="Rotate Animation"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />

    <Button
        android:id="@+id/fadeBtn"
        android:text="Fade Animation"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />

    <Button
        android:id="@+id/moveBtn"
        android:text="Move Animation"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />

    <Button
        android:id="@+id/zoomBtn"
        android:text="Zoom Animation"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />

    <Button
        android:id="@+id/stopBtn"
        android:text="Stop Animation"
        android:layout_width="wrap_content"
</manifest>Develop a application to add animations to ImageView,Move,blink,fade,clockwise,zoom,slide operations are perform in android studio.

```
## Blink.xml
```
<?xml version="1.0" encoding="utf-8"?>
<alpha xmlns:android="http://schemas.android.com/apk/res/android"
    android:fromAlpha="0.0"
    android:toAlpha="1.0"
    android:duration="500"
    android:repeatMode="reverse"
    android:repeatCount="infinite" />

```
## Rotate.xml
```
<?xml version="1.0" encoding="utf-8"?>
<rotate xmlns:android="http://schemas.android.com/apk/res/android"
    android:fromDegrees="0"
    android:toDegrees="360"
    android:pivotX="50%"
    android:pivotY="50%"
    android:duration="1000"
    android:repeatCount="infinite" />

```
## Fade.xml
```
<?xml version="1.0" encoding="utf-8"?>
<alpha xmlns:android="http://schemas.android.com/apk/res/android"
    android:fromAlpha="1.0"
    android:toAlpha="0.0"
    android:duration="2000"
    android:repeatMode="reverse"
    android:repeatCount="infinite" />

```
## Move.xml
```
<?xml version="1.0" encoding="utf-8"?>
<translate xmlns:android="http://schemas.android.com/apk/res/android"
    android:fromXDelta="0"
    android:toXDelta="200"
    android:fromYDelta="0"
    android:toYDelta="200"
    android:duration="1500"
    android:repeatMode="reverse"
    android:repeatCount="infinite" />

```
## Zoom.xml
```
<?xml version="1.0" encoding="utf-8"?>
<scale xmlns:android="http://schemas.android.com/apk/res/android"
    android:fromXScale="1.0"
    android:toXScale="1.5"
    android:fromYScale="1.0"
    android:toYScale="1.5"
    android:pivotX="50%"
    android:pivotY="50%"
    android:duration="1000"
    android:repeatMode="reverse"
    android:repeatCount="infinite" />

```

## OUTPUT
Blink
<img width="1920" height="1080" alt="Screenshot 2025-10-28 143935" src="https://github.com/user-attachments/assets/eb8dde40-2f2c-4b9e-9e43-2a344e68c432" />
Fade
<img width="1920" height="1080" alt="Screenshot 2025-10-28 143947" src="https://github.com/user-attachments/assets/eba5ec3a-755b-48bf-af1e-06bdbec20401" />
Zoom
<img width="1920" height="1080" alt="Screenshot 2025-10-28 144028" src="https://github.com/user-attachments/assets/f4c94da2-265b-40ee-83a4-4bcd65fa6cda" />
Rotate
<img width="1920" height="1080" alt="Screenshot 2025-10-28 144121" src="https://github.com/user-attachments/assets/73abd1f1-3168-49fc-9509-6b6df3129e28" />
Move
![WhatsApp Image 2025-10-28 at 14 43 49_60836d40](https://github.com/user-attachments/assets/54db1fcf-8fb9-4001-a1c8-4be80ae7f40f)
Stop Animation
<img width="1920" height="1080" alt="Screenshot 2025-10-28 143935" src="https://github.com/user-attachments/assets/84065cd9-2637-4c62-9a73-1da3c67659fb" />

## RESULT
Thus,the experiment Implementation of Animation application using android studio executed successfully.
