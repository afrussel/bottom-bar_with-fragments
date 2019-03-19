# bottom-bar_with-fragments
This is an example of android bottombar navigation with fragments. Bottom Navigation Bar always stays at the bottom of your application and provides navigation between the views of your application


 BottomNavigationView in Support Library 28/Jetpack natively supports always having text label.
 
 in XML, use this app:labelVisibilityMode="labeled"
 
 
 <android.support.design.widget.BottomNavigationView
        android:id="@+id/navigation"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:background="@color/colorNavIcon"
        app:itemIconTint="@color/colorPrimaryDark"
        app:itemTextColor="@color/colorNavText"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:labelVisibilityMode="labeled"
        app:menu="@menu/navigation" />

Credits
-------

Author: [Ahmed Faisal](https://github.com/afrussel)



![screenshot](https://github.com/afrussel/bottom-bar_with-fragments/blob/master/bottom_bar_navigation.png "screenshot")
