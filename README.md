Christoffel  App
Christoffel, a React Native mobile application designed for managing and browsing a   Barista Bliss by Christoffel menu items. 
This app provides an intuitive interface for customers to explore beverages, main meals,    
and desserts while allowing cafe staff to manage menu items efficiently.

Technical Implementation
Built with React Native and TypeScript, the app leverages React Navigation for seamless screen transitions. The stack navigator handles navigation between the welcome screen,
home screen, add item form, and filter view. State management
is handled through React hooks, with useState maintaining the menu items list throughout the app lifecycle.

Project Structure
The main App.tsx file serves as the entry point, managing navigation and global state. Screen components are organized in a screens folder, 
with WelcomeScreen handling the initial landing page, HomeScreen displaying the full menu with averages, 
AddItemScreen providing the form for new items, and FilterScreen enabling category-based filtering. 
Type definitions are centralized in type.ts, defining interfaces for CafeItem, Course categories, and navigation parameters.

Changelog
> Updated background color scheme from default to warm burgundy and coral tones for a more inviting cafe atmosphere

> Redesigned card backgrounds to complement the new color palette with enhanced visual contrast

> Integrated @react-native-picker/picker component for improved category selection functionality

> Modified picker styling with custom dropdown icon color and refined border treatments

> Enhanced text color scheme across all screens for better readability against new backgrounds

> Adjusted input field colors to dark brown tones that harmonize with the overall warm aesthetic

>Configured the picker with dropdown mode for Android users, ensuring a familiar native experience that matches platform conventions and user expectations

> Customized the picker's dropdown icon color to a translucent orange-red (#f34a12a6), creating a subtle visual indicator that complements the overall warm color scheme without overwhelming the interface

> Applied custom styling to the picker container with rounded corners (12px border radius) and matching border colors, ensuring the component feels integrated rather than appearing as a generic form element

> Set explicit color values for picker items (#f5e9d7) to maintain text readability when the dropdown menu opens, preventing the default system colors from clashing with the custom theme



