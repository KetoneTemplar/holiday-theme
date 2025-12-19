/* christmas.css */

/* General background and font */
body {
  background-color: #b30000; /* festive red */
  font-family: "Comic Sans MS", cursive, sans-serif;
  color: #ffffff;
  margin: 0;
  padding: 0;
}

/* Header styling */
header {
  background-color: #006400; /* deep green */
  text-align: center;
  padding: 20px;
  font-size: 2em;
  font-weight: bold;
  border-bottom: 5px solid #ffffff;
}

/* Buttons */
button {
  background-color: #006400;
  color: #ffffff;
  border: 2px solid #ffffff;
  padding: 10px 20px;
  margin: 10px;
  font-size: 1em;
  border-radius: 8px;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #ff0000; /* red hover */
  cursor: pointer;
}

/* Snowflake animation */
.snowflake {
  position: fixed;
  top: -10px;
  color: #ffffff;
  font-size: 1.5em;
  animation: fall 10s linear infinite;
}

@keyframes fall {
  0% { top: -10px; opacity: 1; }
  100% { top: 100%; opacity: 0; }
}

/* Footer */
footer {
  background-color: #006400;
  text-align: center;
  padding: 10px;
  font-size: 0.9em;
  border-top: 5px solid #ffffff;
}
