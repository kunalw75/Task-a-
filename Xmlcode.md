<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:gravity="center"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textViewTime"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:text="00:00:00"
        android:textSize="30sp" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:orientation="horizontal">

        <Button
            android:id="@+id/buttonStart"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Start" />

        <Button
            android:id="@+id/buttonStop"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:enabled="false"
            android:text="Stop" />

        <Button
            android:id="@+id/buttonReset"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:enabled="false"
            android:text="Reset" />

    </LinearLayout>

</LinearLayout>
