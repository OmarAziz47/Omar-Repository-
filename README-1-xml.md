# Omar-Repository-
Baloot Counter
<?xml version="1.0" encoding="utf-8"?>
  <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/activity_main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#111"
    tools:context="com.example.android.balootcounter.MainActivity">

<RelativeLayout
    android:layout_width="match_parent"
    android:layout_height="100dp"
    android:background="#111"
    android:id="@+id/view"
    android:layout_alignParentTop="true"
    android:layout_alignParentStart="true">

    <TextView
        android:paddingBottom="16dp"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:textAlignment="center"
        android:id="@+id/text"
        android:textSize="32sp"
        android:textColor="#ffff"
        android:layout_width="205dp"
        android:layout_height="60dp"
        />
</RelativeLayout>

<RelativeLayout
    android:layout_centerHorizontal="true"
    android:layout_width="205dp"
    android:layout_height="210dp"
    android:id="@+id/relativeLayout"
    android:layout_below="@+id/view"
    android:layout_marginStart="65dp">
<TextView
    android:paddingStart="6dp"
    android:paddingTop="16dp"
    android:layout_alignParentStart="true"
    android:id="@+id/us"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="لهم"
    android:textColor="#808080"
    android:paddingBottom="25dp"
    android:textSize="25sp"/>
    <TextView
        android:paddingStart="8dp"
        android:id="@+id/SecLeft"
        android:paddingBottom="20dp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="0"
        android:textSize="48dp"
        android:textColor="#808080"
        android:layout_below="@+id/us"
        android:layout_alignParentStart="true" />
    <EditText
        android:text="0"
        android:layout_alignParentStart="true"
    android:layout_below="@+id/SecLeft"
    android:id="@+id/counter_us"
    android:layout_width="50dp"
    android:layout_height="wrap_content"
    android:textColor="#808080"
    android:inputType="number"/>
    <TextView
        android:paddingEnd="12dp"
        android:paddingTop="16dp"
        android:layout_alignParentEnd="true"
        android:id="@+id/them"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="لنا"
        android:textColor="#808080"
        android:paddingBottom="25dp"
        android:textSize="25sp"/>
    <TextView
        android:paddingEnd="8dp"
        android:id="@+id/SecRight"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="48dp"
        android:text="0"
        android:paddingBottom="20dp"
        android:textColor="#808080"
        android:layout_below="@+id/them"
        android:layout_alignParentEnd="true" />
    <EditText
        android:layout_alignParentEnd="true"
        android:layout_below="@+id/SecRight"
        android:id="@+id/counter_them"
        android:layout_width="50dp"
        android:layout_height="wrap_content"
        android:text="0"
        android:inputType="number"
        android:textColor="#808080"
        />


</RelativeLayout>
    <Button
        android:onClick="enter"
        android:background="#3B9C9C"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="35dp"
        android:layout_below="@+id/relativeLayout"
        android:layout_height="32dp"
        android:layout_width="190dp"
        android:text="سجل"
        android:textColor="#ffff"
        android:textSize="25sp"
        />

<RelativeLayout
android:layout_centerHorizontal="true"

android:layout_width="match_parent"
android:layout_height="100dp"
android:background="#111"
android:layout_alignParentBottom="true">
<Button
    android:id="@+id/reset_button"
    android:text="Reset"
    android:onClick="reset"
    android:layout_marginTop="30dp"
    android:layout_width="85dp"
    android:layout_height="40dp"
    android:background="#000"
    android:textColor="#808080"
    android:layout_centerHorizontal="true"
    android:layout_centerVertical="true">
</Button>

</RelativeLayout>
</RelativeLayout>
 ..
 ..
 ..
