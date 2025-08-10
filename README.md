# 🌡️ Temperature Converter (My First JavaScript Project)

Convert temperatures from **Kelvin** to **Celsius**, **Fahrenheit**, and **Newton** scales.  
This is my **first JavaScript project**, made to learn variables, math operations, and console output formatting.

![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-green?logo=node.js&logoColor=white)
![Beginner Friendly](https://img.shields.io/badge/First%20Project-Friendly-brightgreen)

---

## 📜 Code

```javascript
/*
 🌡️ Temperature Converter
 First JavaScript Project
*/

// Kelvin temperature
const kelvin = 293;

// Convert Kelvin to Celsius
const celsius = kelvin - 273;

// Convert Celsius to Fahrenheit
let fahrenheit = Math.floor(celsius * (9 / 5) + 32);

// Convert Celsius to Newton
let newton = Math.floor(celsius * (33 / 100));

// Output results
console.log("🔥 Temperature Converter Results 🔥");
console.log("----------------------------------");
console.log(`Kelvin: ${kelvin}K`);
console.log(`Celsius: ${celsius}°C`);
console.log(`Fahrenheit: ${fahrenheit}°F`);
console.log(`Newton: ${newton}°N`);
console.log("----------------------------------");
console.log("✅ Conversion Complete!");
