
# Customized and Expandable TextView

Simple library to change the Textview as rectangle, circle and square shapes by adding one line of code in xml file.Multiple features are implemented and wrapped into single textview.

# Features  

1.Textview shape  -> rectangle, square and circle shapes   
2.Expandable textview  
3.Font change via xml   
4.UnderLine textview via xml    
5.Strike through text via xml    
6.CheckedTextView      

the above features are done through xml file.

<a href="http://www.methodscount.com/?lib=com.libRG%3Acustomtextview%3A1.2"><img src="https://img.shields.io/badge/Methods count-195-e91e63.svg"/></a>    <a href="http://www.methodscount.com/?lib=com.libRG%3Acustomtextview%3A1.2"><img src="https://img.shields.io/badge/Size-30 KB-e91e63.svg"/></a>

<a href='https://bintray.com/rajagopalr3/CustomizedTextView/CustomTextView/_latestVersion'><img src='https://api.bintray.com/packages/rajagopalr3/CustomizedTextView/CustomTextView/images/download.svg'></a>

<a href='https://bintray.com/rajagopalr3/CustomizedTextView/CustomTextView?source=watch' alt='Get automatic notifications about new "CustomTextView" versions'><img src='https://www.bintray.com/docs/images/bintray_badge_color.png'></a><a href='https://bintray.com/rajagopalr3/CustomizedTextView/CustomTextView?source=watch' alt='Get automatic notifications about new "CustomTextView" versions'><img src='https://www.bintray.com/docs/images/bintray_badge_color.png'></a>

 ![Screenshot](screenshot1.png)

# Usage
To add CustomTextView into your project, import .aar as module or add through to gradle. 


Add it in your app build.gradle at the end of repositories if not present in gradle file:

```

# Gradle Depedencies :

dependencies {
    implementation 'com.libRG:customtextview:1.6'
}

```
# Import as Module

[Donwload module])https://github.com/Rajagopalr3/CustomizedTextView/blob/rajgopalr3/customtextview-1.6.aar


# XML

```
 <com.libRG.CustomTextView
                android:id="@+id/c6"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_margin="10dp"
                android:padding="10dp"
                android:text="CheckedTextView"
                android:textColor="@color/colorPrimary"
                android:visibility="visible"
                app:lib_checkMarkTint="@color/colorPrimary"
                app:lib_checkedDrawable="@drawable/ic_checked_img"
                app:lib_checkedIconPosition="left"
                app:lib_setChecked="true"
                app:lib_setCheckedText="true"
                app:lib_setFont="@string/droidSansBold"
                app:lib_setRadius="3dp"
                app:lib_setRoundedBorderColor="@color/colorPrimary"
                app:lib_setRoundedView="true"
                app:lib_unCheckedDrawable="@drawable/ic_unchecked_img"/>

                      
```


# Set Font
  Add your font files into assets folder. In string.xml files find your font files like below

```
    <string name="DroidSansBold">DroidSans-Bold.ttf</string>
    
```
# Change Logs [v1.6]

 1. Bug fixes - creating customtextview by programmatically
 2. Removed unused lines in library
 
# Change Logs [v1.3]

 1. Able to change the expanded and collapse hint  
 2. Bug fixes.

# Change Logs [v1.2]

New feature:

 1. Added strike through text  
 2. Added CheckedTextView with custom listener.
 3. We can set custom drawables, drawableTint color for checked & unchecked states

Bug Fixes:

 1. Fixed the click events in various views like event in underlineText view, rectangle text.
 2. Removed unused codes.



# Attributes

 |        Attributes          |            Description            |         Default Value         |
 | ------------------------   | -------------------------------   | --------------------------    |
 | lib_setRoundedView         | if true rounded view enabled      |  false in default             |
 | lib_setShape               | if roundedview true, set shape    |  rectangle in default         |
 | lib_setStrokeWidth         | set stroke width in dp            |  1 dp in default              |
 | lib_setRoundedBorderColor  | set stroke color                  |  current theme's accent color |
 | lib_setRadius              | set corner radius of rectangle    |  1 dp in default              |
 | lib_setRoundedBGColor      | set BG color of rectangle,circle  |  transparent color in default |
 | lib_setFont                | set font name in string           |  android's default font       |
 | lib_setExpandableText      | if true expandable text enabled   |  false in default             |
 | lib_setActionTextVisible   | set visibility if action text     |  false in default             |
 | lib_setActionTextColor     | set color of action text          |  current theme's accent color |
 | lib_setTrimLines           | set lines to trim in textview     |  0 in default                 |
 | lib_setUnderLineText       | set underline to text in textview |  false in default             |
 | lib_setStrikeText          | set strike through text in view   |  false in default             |
 | lib_setCheckedText         | set checked mode enable in view   |  false in default             |
 | lib_setChecked             | change state as checked|unchecked |  unchecked state in default   |
 | lib_checkedDrawable        | set checked drawable icon         |  default checked icon added   |
 | lib_unCheckedDrawable      | set unchecked drawable icon       |  default unchecked icon added |
 | lib_checkMarkTint          | set drawable color in textview    |  default color                |
 | lib_checkedIconPosition    | set checkBox position             |  right side in default        |
 | lib_checkedDrawablePadding | set checkBox padding in view      |  5dp in default               |
 | lib_setExpandHint          | set readmore hint like "show more"|  "more" in default            |
 | lib_setCollapseHint        | set readless hint like "less"     |  "less" in default            |



