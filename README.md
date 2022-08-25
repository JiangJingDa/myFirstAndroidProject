

## **一、实验目标**

模仿微信“发现”页创建列表布局，学习使用Textview imageview、LinearLayout



## 二、实验步骤

### 1. 在activity_main.xml文件下使用LinearLayout进行布局

activity_main.xml文件代码：

``` xml
<?xml version="1.0" encoding="utf-8" ?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:background="#e5e5e5"
    android:layout_height="match_parent"
    android:orientation="vertical">
    <LinearLayout
        android:background="#fff"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="60dp">
        <ImageView
            android:layout_marginLeft="15dp"
            android:layout_gravity="center_vertical"
            android:background="@mipmap/icon_pengyou"
            android:layout_width="40dp"
            android:layout_height="40dp"/>
        <TextView
            android:layout_marginLeft="15dp"
            android:textStyle="bold"
            android:textColor="#333"
            android:textSize="18dp"
            android:gravity="center_vertical"
            android:layout_weight="1"
            android:text="朋友圈"
            android:layout_width="0dp"
            android:layout_height="match_parent"/>
            <ImageView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:background="@mipmap/right"
                android:layout_marginRight="15dp"
                android:layout_gravity="center_vertical"/>

    </LinearLayout>
    <LinearLayout
        android:background="#fff"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:layout_marginTop="20dp">
        <ImageView
            android:layout_marginLeft="15dp"
            android:layout_gravity="center_vertical"
            android:background="@mipmap/two"
            android:layout_width="40dp"
            android:layout_height="40dp"/>
        <TextView
            android:layout_marginLeft="15dp"
            android:textStyle="bold"
            android:textColor="#333"
            android:textSize="18dp"
            android:gravity="center_vertical"
            android:layout_weight="1"
            android:text="扫一扫"
            android:layout_width="0dp"
            android:layout_height="match_parent"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@mipmap/right"
            android:layout_marginRight="15dp"
            android:layout_gravity="center_vertical"/>

    </LinearLayout>
    <LinearLayout
        android:background="#e5e5e5"
        android:layout_width="match_parent"
        android:layout_height="3dp"
        android:orientation="horizontal"/>
    <LinearLayout
        android:background="#fff"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="60dp">
        <ImageView
            android:layout_marginLeft="15dp"
            android:layout_gravity="center_vertical"
            android:background="@mipmap/three"
            android:layout_width="40dp"
            android:layout_height="40dp"/>
        <TextView
            android:layout_marginLeft="15dp"
            android:textStyle="bold"
            android:textColor="#333"
            android:textSize="18dp"
            android:gravity="center_vertical"
            android:layout_weight="1"
            android:text="摇一摇"
            android:layout_width="0dp"
            android:layout_height="match_parent"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@mipmap/right"
            android:layout_marginRight="15dp"
            android:layout_gravity="center_vertical"/>

    </LinearLayout>
    <LinearLayout
        android:background="#fff"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:layout_marginTop="20dp">
        <ImageView
            android:layout_marginLeft="15dp"
            android:layout_gravity="center_vertical"
            android:background="@mipmap/four"
            android:layout_width="40dp"
            android:layout_height="40dp"/>
        <TextView
            android:layout_marginLeft="15dp"
            android:textStyle="bold"
            android:textColor="#333"
            android:textSize="18dp"
            android:gravity="center_vertical"
            android:layout_weight="1"
            android:text="看一看"
            android:layout_width="0dp"
            android:layout_height="match_parent"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@mipmap/right"
            android:layout_marginRight="15dp"
            android:layout_gravity="center_vertical"/>

    </LinearLayout>
    <LinearLayout
        android:background="#e5e5e5"
        android:layout_width="match_parent"
        android:layout_height="3dp"
        android:orientation="horizontal"/>
    <LinearLayout
        android:background="#fff"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="60dp">
        <ImageView
            android:layout_marginLeft="15dp"
            android:layout_gravity="center_vertical"
            android:background="@mipmap/five"
            android:layout_width="40dp"
            android:layout_height="40dp"/>
        <TextView
            android:layout_marginLeft="15dp"
            android:textStyle="bold"
            android:textColor="#333"
            android:textSize="18dp"
            android:gravity="center_vertical"
            android:layout_weight="1"
            android:text="搜一搜"
            android:layout_width="0dp"
            android:layout_height="match_parent"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@mipmap/right"
            android:layout_marginRight="15dp"
            android:layout_gravity="center_vertical"/>

    </LinearLayout>
    <LinearLayout
        android:background="#fff"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:layout_marginTop="20dp">
        <ImageView
            android:layout_marginLeft="15dp"
            android:layout_gravity="center_vertical"
            android:background="@mipmap/six"
            android:layout_width="40dp"
            android:layout_height="40dp"/>
        <TextView
            android:layout_marginLeft="15dp"
            android:textStyle="bold"
            android:textColor="#333"
            android:textSize="18dp"
            android:gravity="center_vertical"
            android:layout_weight="1"
            android:text="购物"
            android:layout_width="0dp"
            android:layout_height="match_parent"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@mipmap/right"
            android:layout_marginRight="15dp"
            android:layout_gravity="center_vertical"/>
    </LinearLayout>
    <LinearLayout
        android:background="#e5e5e5"
        android:layout_width="match_parent"
        android:layout_height="3dp"
        android:orientation="horizontal"/>
    <LinearLayout
        android:background="#fff"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="60dp">
        <ImageView
            android:layout_marginLeft="15dp"
            android:layout_gravity="center_vertical"
            android:background="@mipmap/seven"
            android:layout_width="40dp"
            android:layout_height="40dp"/>
        <TextView
            android:layout_marginLeft="15dp"
            android:textStyle="bold"
            android:textColor="#333"
            android:textSize="18dp"
            android:gravity="center_vertical"
            android:layout_weight="1"
            android:text="游戏"
            android:layout_width="0dp"
            android:layout_height="match_parent"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@mipmap/right"
            android:layout_marginRight="15dp"
            android:layout_gravity="center_vertical"/>

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:layout_marginTop="20dp"
        android:background="#fff"
        android:orientation="horizontal">

        <ImageView
            android:layout_width="40dp"
            android:layout_height="40dp"
            android:layout_gravity="center_vertical"
            android:layout_marginLeft="15dp"
            android:background="@mipmap/eight" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_marginLeft="15dp"
            android:layout_weight="1"
            android:baselineAligned="false"
            android:gravity="center_vertical"
            android:text="小程序"
            android:textColor="#333"
            android:textSize="18dp"
            android:textStyle="bold" />

        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center_vertical"
            android:layout_marginRight="15dp"
            android:background="@mipmap/right" />
    </LinearLayout>
</LinearLayout>

```

## 三、程序运行结果

![image-20220825172700126](C:\Users\姜景达\AppData\Roaming\Typora\typora-user-images\image-20220825172700126.png)

## 四、问题总结与体会

学习了LinearLayout线性布局以及Textview imageview等组件，明白了安卓页面的基本编写方法