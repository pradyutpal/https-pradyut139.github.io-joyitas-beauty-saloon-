<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/12.3.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/12.3.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyDjnaQoWcvE72GSJ7WEyz5p6SRgUUsvkXo",
    authDomain: "joyitas-beauty-saloon-c6313.firebaseapp.com",
    databaseURL: "https://joyitas-beauty-saloon-c6313-default-rtdb.asia-southeast1.firebasedatabase.app",
    projectId: "joyitas-beauty-saloon-c6313",
    storageBucket: "joyitas-beauty-saloon-c6313.firebasestorage.app",
    messagingSenderId: "907285469978",
    appId: "1:907285469978:web:09c8dfc870ed7ecab8aaa3",
    measurementId: "G-J9WC5YJLVE"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
