Ephraim Slider 🎚️
<!-- Add your main screenshot here -->

Ephraim Slider is a sleek, customizable, and smooth React Native slider designed for seamless user interaction. It supports gesture-based control, dynamic progress tracking, and a modern UI that enhances any mobile app experience.

✨ Features
✅ Fully customizable (colors, size, animations)
✅ Supports React Native Reanimated for smooth interactions
✅ Gesture-based control using react-native-gesture-handler
✅ Lightweight & high performance
✅ Works with Expo & React Native CLI
✅ Compatible with iOS & Android

📸 Screenshots
Light Mode	Dark Mode
	
🚀 Installation
Install the package via npm or yarn:

sh
Copy
Edit
npm install @devtar/ephraim-slider --save  
# or  
yarn add @devtar/ephraim-slider  
Also, install required peer dependencies:

sh
Copy
Edit
npm install react-native-gesture-handler react-native-reanimated react-native-svg  
For Expo projects, ensure you have @expo/vector-icons installed:

sh
Copy
Edit
npm install @expo/vector-icons  
🔧 Usage
Basic Example
jsx
Copy
Edit
import EphraimSlider from '@devtar/ephraim-slider';  
import React from 'react';  
import { View } from 'react-native';  

const App = () => {  
  return (  
    <View style={{ flex: 1, justifyContent: 'center', alignItems: 'center' }}>  
      <EphraimSlider  
        min={0}  
        max={100}  
        step={1}  
        value={50}  
        onChange={(val) => console.log(val)}  
      />  
    </View>  
  );  
};  

export default App;  
🎨 Customization
Ephraim Slider is highly customizable with props:

Prop	Type	Default	Description
min	number	0	Minimum value of the slider
max	number	100	Maximum value of the slider
step	number	1	Step value for increments
value	number	0	Initial slider value
onChange	function	() => {}	Callback for value change
trackColor	string	#ccc	Color of the track
thumbColor	string	#000	Color of the thumb
📌 Requirements
React Native 0.68+

Expo SDK 49+ (for Expo users)

Peer Dependencies:

react-native-reanimated

react-native-gesture-handler

react-native-svg

🛠️ Development & Contribution
Want to improve Ephraim Slider? Feel free to fork, contribute, or report issues!

Clone the repo:

sh
Copy
Edit
git clone https://github.com/Ephraim5/ephraim-slider.git  
Install dependencies:

sh
Copy
Edit
cd ephraim-slider  
npm install  
Run the example app (optional):

sh
Copy
Edit
cd example && npm start  
Make changes and create a Pull Request 🚀

📜 License
This project is licensed under the Creative Commons Attribution-NonCommercial (CC BY-NC 4.0) License. This means:

You CAN use and modify it for personal & non-commercial projects.

You CANNOT sell it or use it in commercial products.

You must give credit to the original author.

For more details, check the license file.

💬 Support & Contact
For questions, issues, or feature requests, open an issue or contact me at [your email/contact info].

🚀 Made with ❤️ by Ephraim Senior Dev