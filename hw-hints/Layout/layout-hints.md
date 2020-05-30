# AS2 - Layout Hints (All parts)

## Parts 1-2
	- center your images + maintain aspect ratio (see this: https://developer.android.com/reference/android/widget/ImageView.ScaleType)
	- remember to give all images an ID number!
	- margin value is given to you (vMargin)
	- there should also be more pre-set values that you can use, no need to use Magic Numbers


## Parts 3-4
	- remember to add your ConstraintLayout to Part2View --> like addView(...)
	- What does "inflate" mean exactly?
		- taking the layout XML, parsing it to create view objects in memory, allowing you to later add & modify stuff w/ Java
		(programmatically), then add this view (the whole XML) to activity on runtime.
		- TLDR; convert XML stuff --> Java accessible
	- "Inflate R.layout.part3_grid_solution and add it to this View" --> 	(see this: https://developer.android.com/reference/android/view/LayoutInflater?hl=en) 
		- inflate(int resource, ViewGroup root)
		- resource is the XML file you want to inflate
	- Your "imitation" layout should look very similar to the website/app you're trying to copy
		- you'll get docked if it isn't similar enough... (missing buttons, labels, etc)
