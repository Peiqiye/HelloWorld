# helloWorld
-------------------------------------------------------------
主要代码
MainActivity.java
------------------------
package com.example.asus.helloworld;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.util.Log;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.i("MainActivityLife","调用onCreate()");
    }
    @Override
    protected void onStart(){
        super.onStart();
        Log.i("MainActivityLife","调用onStart()");
    }
    @Override
    protected void onResume(){
        super.onResume();
        Log.i("MainActivityLife","调用onResume()");
    }
    @Override
    protected void onPause(){
        super.onPause();
        Log.i("MainActivityLife","调用onPause()");
    }
    @Override
    protected void onStop(){
        super.onStop();
        Log.i("MainActivityLife","调用onStop()");
    }
    @Override
    protected void onDestroy(){
        super.onDestroy();
        Log.i("MainActivityLife","调用onDestroy()");
    }
    @Override
    protected void onRestart(){
        super.onRestart();
        Log.i("MainActivityLife","调用onRestart()");
    }
}


1.开始运行：

![image](https://github.com/Peiqiye/image/blob/master/图片1.png)

2.后台运行：

![image](https://github.com/Peiqiye/image/blob/master/图片2.png)

3.再次打开：

![image](https://github.com/Peiqiye/image/blob/master/图片3.png)

4.结束

![image](https://github.com/Peiqiye/image/blob/master/图片4.png)

5.运行效果截图：

<img weight="300" height="500" src="https://github.com/Peiqiye/image/blob/master/图片5.png"/>


