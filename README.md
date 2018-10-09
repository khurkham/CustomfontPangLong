# CustomfontPangLong
ဢၼ်ၼႆႉတႃႇႁွင်ႉၸႂ်ႉၽွၼ်ႉၼႂ်း Button CheckBox EditText RadioButton Switch TextView ToggleButton

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:layout_behavior="@string/appbar_scrolling_view_behavior"
    tools:context=".MainActivity"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin">




    <dev.android.khurkham.customfontpanglong.fonttailibrary.views.CustomFontEditText
        android:id="@+id/edittext"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:padding="5dp"
        android:hint="ႁူမ်ၸူမ်းႁပ်ႉတွၼ်ႈ!"
        android:layout_alignParentTop="true"
        android:textSize="40sp"
        android:fontFeatureSettings=" 'liga' off"
        android:textColorHint="@android:color/holo_blue_bright"
        app:fonttai="Pang Long"/>

    <dev.android.khurkham.customfontpanglong.fonttailibrary.views.CustomFontTextView
        android:id="@+id/text"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerInParent="true"
        android:padding="5dp"
        android:text="ၶိူဝ်းၶမ်း Text!"
        android:textStyle="italic"
        android:textSize="40sp"
        app:fonttai="Pang Long"/>

    <dev.android.khurkham.customfontpanglong.fonttailibrary.views.CustomFontButton
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/text"
        android:layout_centerInParent="true"
        android:padding="10dp"
        android:text="မႂ်ႇသုင်ၶႃႈ!"
        android:textStyle="normal"
        android:textSize="40sp"
        android:gravity="center"
        app:fonttai="Pang Long"/>


</RelativeLayout>
 siteUrl = 'https://github.com/khurkham/CustomfontPangLong'
    gitUrl = 'https://github.com/khurkhamlangkhur/CustomfontPangLong.git'
