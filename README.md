# QR-Code-Scanner

### **Description of the QR Code Scanner Web Application**

This web application is a **QR Code scanner** that utilizes your device's camera to continuously scan and process QR codes. It is built with **HTML**, **CSS**, and **JavaScript**, and leverages the **HTML5 QR code** library to decode the data.

### **Key Features:**

1. **7/5 Layout:**

   * The screen is divided into two main sections:

     * **Scanner Area (70%)**: This section occupies 70% of the screen width and displays the live feed from your device’s camera. This is where the QR code scanner operates.
     * **Data Display Area (30%)**: This area occupies the remaining 30% of the screen width. It shows the decoded QR code data and provides a user interface for displaying the results.

2. **Continuous Scanning:**

   * The scanner does not stop after detecting a single QR code. It continuously scans for new QR codes, ensuring that the app can handle multiple QR codes being scanned in succession.

3. **Scan Area Overlay:**

   * A semi-transparent overlay with a **green-bordered square** is displayed in the middle of the scanner area. This indicates the area where the QR code should be placed for optimal scanning.

4. **Multiple Result Display:**

   * When a QR code is successfully decoded, the result is appended to the **data display area** on the right side of the screen. Each scan result is shown in a **scrollable list**, allowing users to see multiple scanned results without losing previous ones.

5. **Automatic Scrolling:**

   * As new QR code data is scanned and added to the display area, the screen automatically scrolls to the bottom, ensuring the most recent results are visible to the user.

6. **Live Camera Feed:**

   * The QR scanner uses the device’s rear camera, by default, to capture and scan QR codes. This makes the app suitable for use on mobile devices, laptops, and desktops with a webcam.

### **Technical Details:**

* **Frontend Technology**: The app is built using **HTML5**, **CSS**, and **JavaScript**.
* **QR Code Decoding Library**: The app uses the **html5-qrcode** JavaScript library to handle the scanning and decoding of QR codes.
* **Styling**: The application is styled with **CSS**, providing a simple and functional interface with a responsive design. The layout is flexible and works well on both mobile and desktop devices.
* **Camera Access**: The app asks for permission to use your device’s camera. It uses the rear camera for scanning (if available).

### **Usage Instructions:**

1. **Open the Web Page**: Open the application in your browser. It will prompt you to allow access to your device’s camera.
2. **Scan QR Codes**: Position a QR code within the green scan area. The app will automatically decode the QR code and display the result in the data display area.
3. **View Results**: Multiple scanned QR code results will be shown in the data display section on the right. The results will scroll automatically when new data is added.

### **Applications:**

* This app can be used for various scenarios where QR codes are present, such as:

  * **Event ticket scanning**
  * **Product or service authentication**
  * **Contactless payments**
  * **Educational purposes**
  * **QR-based authentication systems**

### **Limitations:**

* The app relies on the **camera** being available and functional on the device.
* The QR code needs to be clearly visible within the scan area for accurate decoding.

This QR Code scanner is a versatile and easy-to-use tool for scanning and processing QR codes in real-time. It’s suitable for a wide range of use cases where quick, reliable scanning of QR codes is needed.
