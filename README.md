# 📖 Pearl4CVF User Guide: Example with CVPR 2025

This guide will walk you through how to use the **Pearl4CVF** extension to filter and batch download papers of interest from the official CVF website in under 1 minute.

### ⚠️ Step 0: Browser Settings (Crucial!)

Before you begin, **please ensure you disable the "Ask where to save each file before downloading" feature in your browser.** Otherwise, the browser will pop up a "Save As" dialog for *every single paper*, making automatic batch downloading impossible.

---

## 🚀 Detailed Steps

### Step 1: Go to the Paper List Page

1.  Visit the official CVF Open Access page: [https://openaccess.thecvf.com/menu](https://openaccess.thecvf.com/menu)
2.  In the "Main Conference" list, find and click on **CVPR 2025** (or any other year you are interested in).
3.  **Key Point**: After entering the conference page, please click the **"All papers"** link at the top.

> 💡 **Tip**: Pearl needs to run on the list page that contains all paper titles. Please ensure the page displays hundreds or thousands of papers.

### Step 2: Activate the Extension

4.  Wait for the page to load completely, then click the **Pearl icon** in the browser extension toolbar (top right) to open the operation panel.

<img width="1003" height="646" alt="image" src="https://github.com/user-attachments/assets/e146a1c0-a08e-427a-8824-95dea9983262" />

### Step 3: Configure Filter Rules

Enter your filtering conditions in the popup panel based on your needs:

**5. Enter Keywords**

Enter words of interest in the input box.
* Supports fuzzy matching.
* Case-insensitive.
* Separate multiple keywords with **commas** (`,`).

<img width="996" height="805" alt="image" src="https://github.com/user-attachments/assets/9a4aa8d9-5cba-41a9-8197-4c59565abeff" />
<img width="1006" height="798" alt="image" src="https://github.com/user-attachments/assets/a6aed0bc-e519-4212-ad00-3939c145debf" />

**6. Select Logic Mode (Core Feature)**

* 🔴 **OR Mode (Match Any)**
    * **Meaning**: Papers containing **any** of the keywords you entered will be selected.
    * **Scenario**: Suitable for broad searches. *Example: Input `nerf, gaussian` -> Papers with "NeRF" OR "Gaussian" in the title will be downloaded.*
* 🔵 **AND Mode (Match All)**
    * **Meaning**: Papers must contain **all** the keywords you entered simultaneously to be selected.
    * **Scenario**: Suitable for precise targeting of niche fields. *Example: Input `3d, diffusion` -> Only papers containing BOTH "3D" AND "Diffusion" will be downloaded.*

**7. Set Save Folder (Optional)**

Enter a name in the "Folder Name" input box (e.g., `CVPR25_Diffusion`). Downloaded files will be automatically sorted into this subfolder.

### Step 4: Start Filtering & Downloading

1.  Click the **"🔍 Start Scanning"** button.
    * The extension will rapidly iterate through the page. You will see stats at the bottom (e.g., *Scanned: 2350, Matched: 45*).
2.  After confirming the results are correct, click **"📥 Download Selected"**.
3.  **Done!** All PDFs will be automatically renamed to `Paper Title.pdf` and saved to your default download location (or the `CVPR25_Diffusion` subfolder if you set one).

---

## ❓ FAQ

* **Q: Why does the browser keep popping up dialogs after I click download?**
    * A: Please refer to **"Step 0"**. You forgot to turn off the "Ask where to save each file" option in your browser settings.
* **Q: Can searching for `clip` match `clipping`?**
    * A: Yes! Pearl supports smart fuzzy matching. Entering the root word will match all variations.
* **Q: Does it support ICCV or ECCV?**
    * A: Yes. It works on any conference page hosted under `openaccess.thecvf.com`.

---

## 🚀 Installation (How to Get It?)

The code will be open-sourced on GitHub as we continue to update it. It is completely free, and more "Pearl Series" assistants for other databases will be added soon.

**Step 1: Download**
Download `Pearl4CVF.ZIP` from this repository to your local machine and **unzip** it. Please remember the location of the unzipped folder.

**Step 2: Install**

* **For Chrome Users:**
    1.  Go to `chrome://extensions/` in your address bar.
    2.  Toggle on **Developer mode** in the top right corner.
    3.  Click **Load unpacked**.
    4.  Select the unzipped project folder.

<img width="1323" height="1315" alt="image" src="https://github.com/user-attachments/assets/2c63b406-0332-4683-85c3-3356105f418f" />
<img width="2026" height="1191" alt="image" src="https://github.com/user-attachments/assets/1fac60c9-5685-4280-9122-769482dca6a6" />

* **For Edge Users:**
    1.  Go to `edge://extensions/`.
    2.  Find and enable **Developer mode** (usually on the left sidebar).
    3.  The rest of the steps are similar to Chrome.

**Step 3: Enjoy!**

Open the CVPR 2025 page, click the extension icon, and start your "harvest" as demonstrated above!

<img width="2026" height="1191" alt="image" src="https://github.com/user-attachments/assets/a772a86c-dd44-4aa7-b8e2-861388487106" />
<img width="2037" height="1147" alt="image" src="https://github.com/user-attachments/assets/9b5b7b1a-fcfb-4efb-9cad-510d959e9881" />
---

## 📢 Note on Future Updates (Other Databases)

We will soon be uploading plugins tailored for other major academic databases (such as **IEEE Xplore**, **Nature**, **Springer**, etc.). 

Please note that the **installation and usage instructions** for these upcoming plugins will be **identical** to Pearl4CVF. You can simply follow the same steps above to install and use them once they are released.
