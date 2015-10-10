# SearchViewProblem


1.<item android:id="@+id/mi_search"
        android:icon="@drawable/abc"
        android:title="@string/search"
        app:showAsAction="always"
        app:actionViewClass="android.support.v7.widget.SearchView"/>

click the search icon in the actionable the menu listener is now working in MainActivity line 26



2.<item android:id="@+id/mi_search"
        android:icon="@drawable/abc"
        android:title="@string/search"
        app:showAsAction="always|collapseActionView”
        app:actionViewClass="android.support.v7.widget.SearchView"/>


the menu listener is now working in MainActivity , toast show
