# Login Dashboard

### 1. Log in to the system

Log in to the system by filling in the username and password fields in the login form, located on the right side of the landing page.

If accessing this mode for the first time, you may use the test credentials preloaded in the application:

> **Test Credentials**
>
> * **Username:** `testuser1@test.com`
> * **Password:** `testpwd.1`

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/aBYW0oHM7KQ" allowfullscreen></iframe>
</div>


### 2. Optional: upload your own patient folders

Upload your own patient folders containing the lesion files to be classified. This step is optional — you may also upload files later in either Single Patient or Batch Mode.


!> **Warning**: The system heavily relies on naming conventions for each modality. If your files do not follow the expected naming conventions, they will not be processable in Batch Mode. They may still be uploaded manually in Single Patient Mode.


#### File Naming Convention

| Modality             | Expected Filename    |
| -------------------- | -------------------- |
| MTR Amide High Power | `mtr_amide_b1_2_5`   |
| MTR Amide Low Power  | `mtr_amide_b1_0_625` |
| MTR Noe High Power   | `mtr_noe_b1_2_5`     |
| MTR Noe Low Power    | `mtr_noe_b1_0_625`   |
| T1 Map               | `t1_map`             |
| T2 Map               | `t2_map`             |
| T1 Contrast          | `t1c_highres`        |
| T2 Flair             | `flair_highres`      |

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/pq0fNsy91iI" allowfullscreen></iframe>
</div>


### 3. Optional: set a local storage directory

Set a local storage directory by clicking the **Select Local Storage Directory** button. This designates a folder in your file system where the application will save generated files (resampled files, cropped files, saliency heatmaps, and Excel files). If skipped, the application will prompt you to select a directory during your first inference.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/U4V9NoFW1FU" allowfullscreen></iframe>
</div>


### 4. Optional: explore uploaded and generated files

Explore your uploaded and generated files in the **Uploaded Files** table at the bottom of the screen.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/CopdHqapLrc" allowfullscreen></iframe>
</div>


### 5. Select your desired mode of operation

Select your desired mode of operation by clicking **Single Patient Mode** or **Batch Mode** in the middle of the screen. The system will redirect you to the corresponding view.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/uODZj9fD5f8" allowfullscreen></iframe>
</div>


### 6. Log out

To log out, click the red **Logout** button located in the bottom-right corner of the screen.

<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/sCwZX4xIDp0" allowfullscreen></iframe>
</div>

<div style="display:flex; justify-content:space-between; margin-top: 48px; padding-top: 16px; border-top: 1px solid #efefef;">
  <a href="#/cest_ui-user-manual/user-mode/README" style="display:inline-flex; align-items:center; gap:6px; font-size:13.5px; font-weight:500; color:#555; text-decoration:none; padding:8px 14px; border:1px solid #e5e5e5; border-radius:7px;">← User Mode Overview</a>
  <a href="#/cest_ui-user-manual/user-mode/single-patient" style="display:inline-flex; align-items:center; gap:6px; font-size:13.5px; font-weight:500; color:#555; text-decoration:none; padding:8px 14px; border:1px solid #e5e5e5; border-radius:7px;">Single Patient Mode →</a>
</div>

