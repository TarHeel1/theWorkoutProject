ID attribute values

	header
		Applied to a DIV tag. The header, which contains the site logo and search form. 
	content
		Applied to a DIV tag. The content for the page, which may include lists workouts, lists of exercises, or the form for adding a workout or additional exercises. 
	workouts
		Applied to an OL tag. The list of workouts in this representation. This list may contain only one workout.
	exercises
		Applied to an OL tag. The list of exercises in this representation. This list may contain only one exercise.
	search
		Applied to a FORM tag. The form for searching for workouts or exercises.
	addRecord
		Applied to a FORM tag. The forms for adding workouts or exercises.



Class attribute values

	logo
		Applied to a SPAN tag. The logo for the resource.
	workout
		Applied to an LI tag. A representation of an individual workout.
	pageTitle
		Applied to a SPAN tag. The title of a page.
	exercise
		Applied to a SPAN tag. A representation of an individual exercise within a workout.
	sets
		Applied to a SPAN tag. The number of sets performed for a given exercise. 
	reps
		Applied to a SPAN tag. The number of reps performed in each set of a given exercise.
	weight
		Applied to a SPAN tag. The weight used for a given exercise.
	date
		Applied to a SPAN tag. Contains the date the workout was begun.
	time
		Applied to a SPAN tag. Contains the time the workout was begun.



Name attributes values

	workout
		Applied to an INPUT[checkbox] element. An individual workout.
	workoutType
		Applied to a drop-down menu. The classification of a workout (e.g., strength, card)
	exercise
		Applied to a drop-down menu. The name of an exercise.
	workoutMonth
		Applied to a drop-down menu. The name of the month in which the workout was begun.
	workoutDay
		Applied to a drop-down menu. The name of the day in which the workout was begun.
	workoutYear
		Applied to a drop-down menu. The name of the year in which the workout was begun.
	workoutAmpm
		Applied to a drop-down menu. Indicates whether the workout was begun before or after Noon.
	startMonth
		Applied to a drop-down menu. The name of the first month in a date range for searching for workouts.
	startDay
		Applied to a drop-down menu. The name of the first day in a date range for searching for workouts.
	startYear
		Applied to a drop-down menu. The name of the first year in a date range for searching for workouts.
	endMonth
		Applied to a drop-down menu. The name of the final month in a date range for searching for workouts.
	endDay
		Applied to a drop-down menu. The name of the final day in a date range for searching for workouts.
	endYear
		Applied to a drop-down menu. The name of the final year in a date range for searching for workouts.
	exercise
		Applied to a drop-down menu. The name of an exercise.
	sets
		Applied to an INPUT[text] element. The number of sets performed.
	reps
		Applied to an INPUT[text] element. The number of reps performed.
	weight
		Applied to an INPUT[text] element. The amount of weight used.
	time
		Applied to an INPUT[text] element. The length of time an exercise is performed.

Rel attribute values

	all-workouts
		Applied to an A tag. A reference to the list representation of all workouts.
	all-type
		Applied to an A tag. A reference to the list representation of all workouts of a given type.
	all-exercise
		Applied to an A tag. A reference to the list representation of all exercises of a given type.
	workout	
		Applied to an A tag. A reference to the representation of a specific workout. 



Notes:
*"all-workouts.html" stands in place of "/" as outlined in Assignment 3.
*All lists generated using search follow the same URI format, regardless of whether the user is looking for a specific date or date range, or looking for all workouts or only workouts of a particular type. All search variables are included in a URI using GET.
*Add and delete are no longer considered resources as they were specified in Assignment 3.
*"Classification" for types of workouts has been replaced with "workout-type" for greater clarity.
*Since the search function is not operational, search results cannot be reached by clicking through and the example will need to be opened from the directory.