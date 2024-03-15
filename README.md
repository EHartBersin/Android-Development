# Android-Development
This repository contains a collection of assignments completed during the course, Introduction to Mobile Application Development. Each assignment is organized into separate folders for easy navigation.

# Assignments
1. **Assignment 1: Basic UI Layout Modification**
	Focuses on enhancing a basic user interface layout in Android Studio. It involves modifying XML files to change text and add buttons to the UI.

2. **Assignment 2: Sign-Up Form**
	Collects and displays user information. It features a sign-up form with fields for name, email, program selection, password, and password confirmation. Validation ensures all fields are filled, a program is selected, and passwords match. Upon successful validation, a welcome message with the user's name is displayed.

3. **Assignment 3: Custom Color Spinner**
	Enables users to select colors from a Spinner and dynamically changes the background color of the activity's layout. 

4. **Assignment 4: Image Displayer**
	Allows a user to pick an image from a RecyclerView and once selected, display the selected image inside the main activity along with a description.

5. **Assignment 5: Activity Item Selection**
	This is an assignment that utilizes two activities: SelectionActivity and DisplayActivity. Users can select an item in SelectionActivity, which launches DisplayActivity to display details about the selected item. The app features a collection of themed images, each with a corresponding textual description. SelectionActivity uses a custom adapter to present items for selection, and when an item is clicked, DisplayActivity shows its description and image, along with a close button.

6. **Assignment 6: Fragment Item Selector**
	Similar to the previous assignment, but uses a single activity and two Fragments, instead of two activities. The app allows users to explore images with a SelectionFragment for picking images from a RecyclerView and a DisplayFragment for viewing details. Fragments will utilize ViewModels and LiveData for data sharing. SelectionFragment employs a Factory Method to generate instances with a collection of image items. Upon launch, both fragments are placed in FragmentContainerViews, adjusting layout based on device orientation.

7. **Assignment 7: FlossPlayer (Audio Book App)**
	This assignment serves as the intial phase of the final project, and audio book player. It incorporates a Book class for storing book information. Three fragments were integrated: BookListFragment, showcasing audiobook titles in a RecyclerView, BookPlayerFragment, offering details of the selected audiobook, and a third fragment for handling dynamic changes based on device configuration. The implementation also leverages the List-Detail pattern for smooth fragment navigation.

8. **Assignment 8: FlossPlayer (Audio Book Application)**
	Continuing the previous assignment, the Android audiobook player application was enhanced to fetch book information dynamically from a web service API. This allows users to retrieve book titles and perform searches using provided search terms. The Book class was updated to include additional fields like ID and cover URI, and the BookFragment now displays book cover images alongside titles and authors. Integration of a search feature using Android's built-in Search Dialog enables users to find specific books.

9. **Assignment 9: FlossPlayer (Audio Book Application)**
	In the third phase, the FlossPlayer app was enhanced to enable audio playback of audiobooks fetched from a web service. Integration of the PlayerService library allowed streaming of audiobooks with playback controls and progress feedback. The Book class was updated to include duration information, and the FlossAudioBook interface was implemented to support book ID functionality required by the PlayerService. New features included play/pause controls, a "Now Playing" label, and a SeekBar to display playback progress. Audio controls were contained in the BookControlFragment, while playback progress was integrated into the activity. Playback remained uninterrupted during activity restarts, and audio continued even if the user exited and relaunched the app.

10. **Assignment 10: FlossPlayer (Audio Book Application)**
	The final update of the FlossPlayer app introduces seamless streaming and background downloading of audiobooks, along with the ability to resume playback from the last position when pausing or switching between books. Additionally, the app maintains the persistent display of previously searched books upon reopening.
