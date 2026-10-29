# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


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

## Developed by: RAMPRASATH R
## Registeration Number : 212223220086
Program to print the text “Hello World”.
```
package com.example.text;

import android.os.Bundle;
import android.widget.Toast;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onStart() {
        super.onStart();
        Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onPause() {
        super.onPause();
        Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onResume() {
        super.onResume();
        Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onStop() {
        super.onStop();
        Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onDestroy() {
        super.onDestroy();
        Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG).show();
    }
}
```
## OUTPUT
# OnCreate:
<img width="1920" height="1080" alt="create" src="https://github.com/user-attachments/assets/10c3a9d1-66a1-4ed2-8260-dd25125eaa9d" />

# OnStart:
<img width="1920" height="1080" alt="start" src="https://github.com/user-attachments/assets/f233b5e3-2e41-4384-987e-def8a110ce13" />

# OnRestart:
<img width="1920" height="1080" alt="restart" src="https://github.com/user-attachments/assets/f1039c2e-9cc3-49f1-919a-edd96cdd5c96" />

# OnPause:
<img width="1920" height="1080" alt="pause" src="https://github.com/user-attachments/assets/c6c3bfd2-cda0-4c08-81a0-3f765355161f" />

# OnResume:
<img width="1920" height="1080" alt="resume" src="https://github.com/user-attachments/assets/3beb63b2-effe-4240-8e1a-b4f2b4a3f59f" />

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
