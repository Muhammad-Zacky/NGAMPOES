https://docs.google.com/document/d/1c-KAODdoBdc8rRNoqjAqoyxPXvNMviUGnOMLF67CJdU/mobilebasic


<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".activity_page_relative_layout">

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:paddingLeft="16dp"
        android:paddingRight="16dp">

        <EditText
            android:id="@+id/etName"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="reminder"/>

        <Spinner
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:id="@+id/dates"
            android:layout_below="@id/etName"
            android:layout_alignParentRight="true"
            android:layout_toLeftOf="@id/times" />

        <Spinner
            android:layout_width="96dp"
            android:layout_height="wrap_content"
            android:id="@+id/times"
            android:layout_below="@id/etName"
            android:layout_alignParentRight="true"/>

        <Button
            android:layout_width="96dp"
            android:layout_height="wrap_content"
            android:layout_below="@id/times"
            android:layout_alignParentRight="true"
            android:text="DONE"/>

    </RelativeLayout>

</androidx.constraintlayout.widget.ConstraintLayout>





<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:background="#F5F5F5"
    android:padding="16dp">

    <TableLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:stretchColumns="1">

        <TableRow
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="#E0FFFF">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Open ..."
                android:padding="8dp" />

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Ctrl + O"
                android:gravity="right"
                android:padding="8dp" />
        </TableRow>

        <TableRow
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="#E0FFFF">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Save ..."
                android:padding="8dp" />

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Ctrl + S"
                android:gravity="right"
                android:padding="8dp" />
        </TableRow>

        <TableRow
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="#FFFF00">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="X"
                android:padding="8dp" />
        </TableRow>

        <TableRow
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="#FFFF00">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Export"
                android:padding="8dp" />

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Ctrl + E"
                android:gravity="right"
                android:padding="8dp" />
        </TableRow>

        <TableRow
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="#E6E6FA">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Quit"
                android:padding="8dp" />

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Ctrl + Q"
                android:gravity="right"
                android:padding="8dp" />
        </TableRow>

    </TableLayout>
</LinearLayout>
