https://docs.google.com/document/d/1c-KAODdoBdc8rRNoqjAqoyxPXvNMviUGnOMLF67CJdU/mobilebasic


<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="16dp"
    android:background="#FFF8F9FF">

    <!-- EditText for Reminder -->
    <EditText
        android:id="@+id/editTextReminder"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Reminder"
        android:padding="10dp"
        android:background="@android:color/transparent"
        android:textColor="#000"
        android:textSize="18sp" />

    <!-- Spinner for first dropdown -->
    <Spinner
        android:id="@+id/spinner1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/editTextReminder"
        android:layout_marginTop="20dp"
        android:entries="@array/items"
        android:textSize="18sp" />

    <!-- Spinner for second dropdown -->
    <Spinner
        android:id="@+id/spinner2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/editTextReminder"
        android:layout_toRightOf="@id/spinner1"
        android:layout_marginStart="20dp"
        android:entries="@array/items"
        android:textSize="18sp" />

    <!-- Button for Done -->
    <Button
        android:id="@+id/buttonDone"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/spinner1"
        android:layout_alignParentEnd="true"
        android:layout_marginTop="20dp"
        android:text="DONE"
        android:backgroundTint="#6B52AE"
        android:textColor="#FFF"
        android:padding="10dp"
        android:textSize="18sp" />

</RelativeLayout>
