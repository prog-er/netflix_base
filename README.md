Netflix Clone App 🎥
A feature-rich iOS application inspired by Netflix, built using Swift and Xcode. This app demonstrates creating a streaming platform interface, fetching data from APIs, and using modern iOS development practices.

Features
Dynamic Home Screen with categorized movie lists.
Integrated API Fetching using URLSession.
Custom TableViewCells and CollectionViewCells for flexible UI components.
Search Functionality with query results and detailed previews.
YouTube API Integration for fetching and displaying trailers.
Persistent data storage using Core Data.
Navigation bar customization for a seamless user experience.
Modularized codebase with reusable components and models.

Installation
Clone the Repository:

git clone https://github.com/prog-er/netflix-clone.git
cd netflix-clone
Open in Xcode:
Open the NetflixClone.xcodeproj file.
Install Dependencies: Ensure you have CocoaPods installed and run:
pod install

Configure API Keys:

Add your TMDb API Key and YouTube API Key in a .plist file.
Run the App: Select your target device or simulator and press Cmd+R.

App Flow
1. Home Screen
Implements a UITableView with multiple sections for categorized content.
Uses a custom TableViewCell containing a UICollectionView for horizontal scrolling.
2. Search Tab
Allows users to search for titles and view results in a SearchResultsViewController.
Integrates YouTube API to fetch and play trailers.
3. Upcoming Tab
Displays upcoming movies using a dedicated UITableView.
Fetches data from the API and populates the screen dynamically.
4. Movie Details
Clicking on a movie navigates to TitlePreviewViewController, showcasing:
Movie details
Trailer fetched from the YouTube API
Technologies Used
Swift: Programming language for app development.
UIKit: Framework for UI components.
Core Data: Local storage for persistent data.
URLSession: For API requests and data fetching.
YouTube API: For trailer integration.
Notification Center: To handle updates across ViewControllers.
