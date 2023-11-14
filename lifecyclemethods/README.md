## Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.
## AIM:
To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:
Latest Version Android Studio

## ALGORITHM:
Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
Developed by: Sudhindev S
Reg.no:212221040166
```
## activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    style="TIM"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World\nThis is Hiba...!!"
        android:textSize="30dp"
        android:textAppearance="@style/TextAppearance.AppCompat.Large"
        android:textColorHighlight="#FFFFFF"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.455"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.407" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
## MainActivity.java
```
package com.example.hiba;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast t2= Toast.makeText(getApplicationContext(),"OnCreate Executed",Toast.LENGTH_LONG);
        t2.show();
    }
    protected void onStart() {
        super.onStart();
        setContentView(R.layout.activity_main);
        Toast t2= Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG);
        t2.show();
    }
    protected void onResume() {
        super.onResume();
        setContentView(R.layout.activity_main);
        Toast t2= Toast.makeText(getApplicationContext(),"OnResume Executed",Toast.LENGTH_LONG);
        t2.show();
    }
    protected void onPause() {
        super.onPause();
        setContentView(R.layout.activity_main);
        Toast t2= Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG);
        t2.show();
    }
    protected void onRestart() {
        super.onRestart();
        setContentView(R.layout.activity_main);
        Toast t2= Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG);
        t2.show();
    }
    protected void onDestroy() {
        super.onDestroy();
        setContentView(R.layout.activity_main);
        Toast t2= Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG);
        t2.show();
    }
}
```
## Output:
![WhatsApp Image 2023-08-28 at 23 32 39](https://github.com/HibaRajarajeswari/Life-Cycle-Model/assets/129970809/ee9a05c0-6283-4747-ada8-3ddf8390edee)
![WhatsApp Image 2023-08-28 at 23 28 55](https://github.com/HibaRajarajeswari/Life-Cycle-Model/assets/129970809/80d5bc93-9033-422a-ba68-24e61cffd654)
![WhatsApp Image 2023-08-28 at 23 08 33](https://github.com/HibaRajarajeswari/Life-Cycle-Model/assets/129970809/a13c5e0a-39e0-4f7f-8f42-79e2c9bfc08f)
![WhatsApp Image 2023-08-28 at 11 42 02](https://github.com/HibaRajarajeswari/Life-Cycle-Model/assets/129970809/b35ab861-90fa-4b95-9fd1-ead260697a24)
![WhatsApp Image 2023-08-28 at 23 07 04](https://github.com/HibaRajarajeswari/Life-Cycle-Model/assets/129970809/81b1a6fe-2bba-45e0-be7e-e29467d181bc)
![WhatsApp Image 2023-08-28 at 23 08 00](https://github.com/HibaRajarajeswari/Life-Cycle-Model/assets/129970809/979fd650-ce2c-4105-8ea4-5eccf28e9b32)
![WhatsApp Image 2023-08-28 at 23 39 44](https://github.com/HibaRajarajeswari/Life-Cycle-Model/assets/129970809/a685e98c-7912-4e15-a954-6b1f48faf3f7)


## RESULT:
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
