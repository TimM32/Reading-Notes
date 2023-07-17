# Reading Notes Class 43

- Name three Core Components of React Native and describe what they do.
    - <Image>	Displays different types of images
    - <ScrollView>	A generic scrolling container that can contain multiple components and views
    - <TextInput>	Allows the user to enter text
- What problem does React Native solve (why call it native)? The problem with maintaining two code bases for such a big app? Work duplication and, at times, solving the same problem in two different ways. React Native is a straightforward answer to these problems. React Native uses JavaScript to compile the app's user interface, but using native-OS views.
- What are the building blocks of a React Native app? How does that compare to a React app? It has a similar architecture: it uses one-way data binding, and its main building blocks are components. But while React is a JavaScript library, React Native is a native framework written in C. Despite this difference, the core concepts, like state management, are similar across the two frameworks.

- What solution does expo provide? Expo is a framework to build React Native apps. It is a set with tools and services built for React Native. It will help you begin with building React Native apps with ease. It provides you with a list of tools that simplify the creation and testing of React Native app.
- Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow. "managed"
- What is the difference between React Native and Expo? Expo is basically a set with tools and services built on top of React Native. It will help you begin with building React Native apps with ease. It provides you with a list of tools that simplify the creation and testing of React Native apps.

- Checkout this tool. What does snack allow you to do? Expo Snack is an Expo platform designed for running React Native apps in the browser. The code created can be saved as “snacks” and easily shared. Working on Expo Snack, we helped to create a solution that requires no setup, can be previewed and shared instantly.


- What does “eject” mean within the context of Expo? The Expo Eject Step is necessary to eject your app to install any missing native dependencies. Installing the native dependencies is done by our dedicated Steps, such as Install missing Android SDK components and Run CocoaPods install.
- When should you not eject? Limited native customizations, The Expo ecosystem provides for the needs of the app, and Rapid prototyping or proof of concept.
- Why might you choose to eject? Advanced Native integration, Custom build process/specific build requirements, and Complex third party library compatability.

## Additional Information
