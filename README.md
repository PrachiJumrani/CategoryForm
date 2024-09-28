# CategoryForm
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:orientation="vertical"
    android:background="@color/lightGray"
    android:padding="16dp">


    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="20dp"
        app:cardCornerRadius="10dp">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:padding="20dp">


            <TextView
                android:id="@+id/category"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Category Name"
                android:textSize="20sp"
                android:textColor="@color/black" />

            <EditText
                android:id="@+id/categoryName"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginTop="8dp"
                android:background="@drawable/rounded_edittext"
                android:hint="Enter Category Name"
                android:inputType="text"
                android:minHeight="48dp"
                android:padding="10dp" />


            <TextView
                android:id="@+id/budgetLabel"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Set Budget"
                android:textSize="20sp"
                android:textColor="@color/black"
                android:layout_marginTop="16dp" />

            <EditText
                android:id="@+id/budget"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginTop="8dp"
                android:background="@drawable/rounded_edittext"
                android:hint="Enter Budget"
                android:inputType="numberDecimal"
                android:minHeight="48dp"
                android:padding="10dp" />
        </LinearLayout>
    </androidx.cardview.widget.CardView>


    <Button
        android:id="@+id/submitButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Submit"
        android:textColor="@android:color/white"
        android:backgroundTint="@color/colorPrimary"
        android:textSize="20sp"
        android:layout_marginTop="16dp"
        android:background="@drawable/rounded_button" />
</LinearLayout>
