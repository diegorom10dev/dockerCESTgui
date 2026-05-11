# Login Dashboard

{% stepper %}
{% step %}
### Log in to the system

Log in to the system by filling in the username and password fields in the login form, located on the right side of the landing page.

If accessing this mode for the first time, you may use the test credentials preloaded in the application:

> **Test Credentials**
>
> * **Username:** `testuser1@test.com`
> * **Password:** `testpwd.1`

{% embed url="https://youtu.be/aBYW0oHM7KQ" %}
{% endstep %}

{% step %}
### Optional: upload your own patient folders

Upload your own patient folders containing the lesion files to be classified. This step is optional — you may also upload files later in either Single Patient or Batch Mode.

{% hint style="danger" %}
**Warning**: The system heavily relies on naming conventions for each modality. If your files do not follow the expected naming conventions, they will not be processable in Batch Mode. They may still be uploaded manually in Single Patient Mode.
{% endhint %}

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

{% embed url="https://youtu.be/pq0fNsy91iI" %}
{% endstep %}

{% step %}
### Optional: set a local storage directory

Set a local storage directory by clicking the **Select Local Storage Directory** button. This designates a folder in your file system where the application will save generated files (resampled files, cropped files, saliency heatmaps, and Excel files). If skipped, the application will prompt you to select a directory during your first inference.

{% embed url="https://youtu.be/U4V9NoFW1FU" %}
{% endstep %}

{% step %}
### Optional: explore uploaded and generated files

Explore your uploaded and generated files in the **Uploaded Files** table at the bottom of the screen.

{% embed url="https://youtu.be/CopdHqapLrc" %}
{% endstep %}

{% step %}
### Select your desired mode of operation

Select your desired mode of operation by clicking **Single Patient Mode** or **Batch Mode** in the middle of the screen. The system will redirect you to the corresponding view.

{% embed url="https://youtu.be/uODZj9fD5f8" %}
{% endstep %}

{% step %}
### Log out

To log out, click the red **Logout** button located in the bottom-right corner of the screen.

{% embed url="https://youtu.be/sCwZX4xIDp0" %}
{% endstep %}
{% endstepper %}
