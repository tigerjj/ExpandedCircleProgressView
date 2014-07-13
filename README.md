ExpandedCircleProgressView
==========================

this is a custom view for android to show progressing with an expanded circle. 

![Sample ExpandedCircleProgressView](https://raw.github.com/tigerjj/ExpandedCircleProgressView/master/screenshots/sample_animation.gif)  
![ExpandedCircleProgressView](https://raw.github.com/tigerjj/ExpandedCircleProgressView/master/screenshots/sample_01.png)  

### I would like to show progress with diffrent view with circle. For that reason, i made Fancy Buttons, to make this task much easier.

## Overview
**ExpandedCircleProgressView**, helps you to show progress with expading circle. 
**You can get this sample of view on market

### Usage

1. Add ExpandedCircleProgressView namespace on the top element : 

	xmlns:tigerlee="http://schemas.android.com/apk/res-auto" 
	
2. Add namespace of ExpandedCircleProgressView 

  <com.tigerlee.widget.ExpandedCircleProgressView
      android:id="@+id/expanded_circle_progress"
      android:layout_centerInParent="true"
      android:layout_width="match_parent"
      android:layout_height="match_parent" />

####  Supported Attributs

1. declare-styleable 

  <declare-styleable name="ExpandedCircleProgressView">
      <attr name="innerCircleSize" format="dimension" />
      <attr name="outerCircleSize" format="dimension" />
      
      <attr name="innerCircleColor" format="color" />
      <attr name="outerCircleColor" format="color" />
      
      <attr name="textProgressColor" format="color" />
      <attr name="progressCircleColor" format="color" />
      
      <attr name="outerCircleLineWidth" format="dimension" />
      
      <attr name="textProgressSize" format="dimension" />
  </declare-styleable>
    
2. Detail role of attributes

| XML Attribute        | Java Attribute           | Description  |
| ------------- |:-------------:| -----:|
| tigerlee:innerCircleSize      | setInnerCircleSize(int) | Set size of the inner circle |
| tigerlee:outerCircleSize     | setOuterCircleSize(int)| Set size of the inner circle |
| tigerlee:innerCircleColor  | setInnerCircleColor(int)   | Set color of the inner circle |
| tigerlee:outerCircleColor | setOuterCircleColor(int)  | Set color of the outer circle |
| tigerlee:textProgressColor | setProgressTextColor(int)  | Set color of the progress text |
| tigerlee:progressCircleColor | setProgresColor(int)  | Set color of circle of expanding progress |
| tigerlee:outerCircleLineWidth | setOuterCircleLineWidth(int) | Set width of the outer circle line |
| tigerlee:textProgressSize | setTextProgressSize(int)  | Set size of the progress text |

#### Sample

** Add expandedeCircleProgress view on layout**  
  
![ExpandedCircleProgressView](https://raw.github.com/tigerjj/ExpandedCircleProgressView/master/screenshots/sample_02.png)  

  <com.tigerlee.widget.ExpandedCircleProgressView
      android:id="@+id/expanded_circle_progress"
      android:layout_centerInParent="true"
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      tigerlee:innerCircleSize="40dp"
      tigerlee:outerCircleSize="100dp"
      tigerlee:innerCircleColor="@android:color/holo_orange_light"
      tigerlee:outerCircleColor="@android:color/black"
      tigerlee:outerCircleLineWidth="1dp"
      tigerlee:progressCircleColor="@android:color/holo_orange_light"
      tigerlee:textProgressColor="@android:color/white"
      tigerlee:textProgressSize="20sp"
       />

### Qustion?

Horyun Lee

Feel free to email at <tigerejj84@gmail.com>
