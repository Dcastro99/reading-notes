# **React Native**

> ## getting started with react native

1. Name three Core Components of React Native and describe what they do.

<View> (A container that supports layout with flexbox, style, some touch handling, and accessibility controls)
<Text> (Displays, styles, and nests strings of text and even handles touch events)
<Image> (Displays different types of images)

2. What problem does React Native solve (why call it native)?

- It allows you use native UI controls and have full access to the native platform

3. What are the building blocks of a React Native app? How does that compare to a React app?

Text and View are the two most basic building blocks of any React Native application. In REact its just different components. But React renders in HTML and Native renders components.

> ## Exop

1. What solution does expo provide?

- You can quickly publish updates to your app over the app, with ease

2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the `managed` workflow.

3. What is the difference between React Native and Expo?

- Expo is a framework in which to build React Native apps.

> ## expo snack

1. Checkout this tool. What does snack allow you to do?

- It lets you run React Native apps in the browser

> ## ejecting

1. What does “eject” mean within the context of Expo?

- basically its a way to eject your pure js project and can be opened with Xcode and Android Studios and built.

2. When should you not eject?

- You require Expo's push notification services. After ejecting, since Expo no longer manages your push credentials, you'll need to manage your own push notification pipeline.

3. Why might you choose to eject?

- Your Expo project needs a native module that Expo doesn't currently support.
