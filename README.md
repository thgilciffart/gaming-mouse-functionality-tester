Based on the repository's purpose as a tool for diagnosing mouse hardware issues, here is a professional `README.md` file you can use for the project.

-----

# Gaming Mouse Functionality Tester

A web-based diagnostic tool designed to test the performance and hardware integrity of gaming mice. This tool helps users identify common hardware failures such as double-clicking, sensor stuttering, and inconsistent polling rates.

## 🚀 Features
  * **Button Actuation Test:** Verify that all mouse buttons (LMB, RMB, MMB, and side buttons) are registering correctly.
  * **Double-Click Detection:** Uses a configurable millisecond threshold to detect unintended "chatter" or double-clicking caused by worn-out mechanical switches.  * **Scroll Wheel Consistency:** Detects "scroll jumping" or reverse inputs when scrolling in a single direction.
## 🛠️ How to Use

1.  **Open the App:** Navigate to the [hosted version of the tool](https://rainbow-unicorn-dd1074.netlify.app/) (or open `index.html` locally).
2.  **Test Buttons:** Click the designated areas. A counter will track successful clicks and highlight any detected "double-clicks" in red.
3.  **Check Polling Rate:** Move your mouse rapidly across the screen. The real-time graph or text display will show the average and peak polling rate.
4.  **Verify Scroll:** Use the scroll wheel to ensure the directional highlights match your physical movement.

## 🔧 Local Setup

To run this project locally:

1.  Clone the repository:
    ```bash
    git clone https://github.com/thgilciffart/gaming-mouse-functionality-tester.git
    ```
2.  Navigate to the directory:
    ```bash
    cd gaming-mouse-functionality-tester
    ```
3.  Open `index.html` in any modern web browser (Chrome or Edge are recommended for the best polling rate accuracy).

## 📝 Configuration

You can adjust the **Double-Click Threshold** within the settings:

  * **Lower (e.g., 20ms):** More lenient; only flags very fast/obvious hardware errors.
  * **Higher (e.g., 80ms):** Stricter; flags clicks that are physically possible but likely unintended.

## 📄 License

This project is licensed under the [MIT License](https://www.google.com/search?q=LICENSE).
