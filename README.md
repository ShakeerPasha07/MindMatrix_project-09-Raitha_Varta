Raitha-Varta (Agriculture Flash-Card Advisor)
This is a minimal end-to-end Android application developed according to the project specifications. It provides an Instagram-like "Flash-Card" experience for farmers to digest scientific crop advisories efficiently.

Features Included
Daily Tip (ViewPager2): Uses the recommended ViewPager2 for an intuitive swipeable flash-card experience.
Crop Category Filter: A dynamic ChipGroup allowing farmers to filter by [Paddy, Areca nut, Coconut, Tomato].
Success Story Integration: Specific cards display localized success stories natively on the UI.
Expert Ask: A floating action button simulating sending diseased leaf photos to an expert.
Room Database: Implemented Room with Flow to provide an offline-first caching mechanism and instant data loads.
Glide Media Loading: Used Glide to handle and cache high-quality crop/pest images effectively.
Kannada Localization: Flash-cards come packed with dual language text (English and Kannada) to ensure wide accessibility in Karnataka.
How to Run
Open Android Studio.
Select File > Open and select the mindmatrixproject directory.
Android Studio will automatically resolve the build.gradle.kts files and download dependencies.
Run the app on an Emulator or a Physical Device.
Project Structure
app/src/main/java/.../data/: Contains Room Database entities, DAOs, and configuration.
app/src/main/java/.../ui/: Contains the TipAdapter specifically built for ViewPager2.
app/src/main/java/.../MainActivity.kt: Contains UI binding, mock data pre-population, and filtering logic.
app/src/main/res/layout/: Contains the XML layout files for high-contrast visibility on the field.
