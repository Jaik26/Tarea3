# Tarea3
Tarea semana 3 curso de android

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.juan.tareasemana3.TareaSemana3"
    tools:layout_editor_absoluteY="81dp"
    tools:layout_editor_absoluteX="0dp">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:srcCompat="@drawable/marcianito_miprimer_proyecto_android"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="-107dp"
        android:layout_alignParentBottom="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/text_view"
        tools:layout_editor_absoluteY="38dp"
        tools:layout_editor_absoluteX="170dp"
        android:layout_marginTop="104dp"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:textSize="30dp"/>

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/Button"
        tools:layout_editor_absoluteY="104dp"
        tools:layout_editor_absoluteX="157dp"
        android:layout_marginTop="51dp"
        android:layout_below="@+id/textView"
        android:layout_centerHorizontal="true" />

</RelativeLayout>
