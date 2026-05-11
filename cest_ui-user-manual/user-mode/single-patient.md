# Single Patient

{% stepper %}
{% step %}
### Select the desired channel configuration

Select the desired channel configuration to run an inference using the dropdown button in the top-left corner of the left sidebar.

{% hint style="info" %}
Files will not be resampled and populated into the viewer until a channel configuration has been selected.
{% endhint %}

{% embed url="https://youtu.be/wnAfYFQkJyY" %}
{% endstep %}

{% step %}
### Select the patient folder

Select the patient folder containing the files for the automated lesion classification. Either upload a new **patient folder** (not individual files) using the **Upload New Patient Folder** button, or select a previously uploaded folder using the **Select Uploaded Folder** button.

{% embed url="https://youtu.be/jTeCs_AQaYk" %}
{% endstep %}

{% step %}
### Verify the auto-matched modalities

Verify that all auto-matched modalities have selected the correct files. If any modality could not be auto-matched, or if a file was matched incorrectly, manually upload the appropriate file using the **Change** button inside the modality's box.

{% embed url="https://youtu.be/p9xXChNtl_w" %}
{% endstep %}

{% step %}
### Select the desired lesion

Select the desired lesion to run the inference on, using the same **Change** button from step 3.2.3 if the default lesion is not your intended one.

{% embed url="https://youtu.be/DBwVexcoEEU" %}

{% hint style="warning" %}
While multiple lesions for the same patient can be classified, this mode only allows one lesion to be processed at a time. If a new lesion for the same patient needs to be processed, it is **strongly recommended to reload the page** by pressing **Ctrl + F5** on the keyboard, or by clicking the refresh symbol in the browser.
{% endhint %}

{% embed url="https://youtu.be/xnWMgOZYr8w" %}
{% endstep %}

{% step %}
### Select the resampled file

Select the resampled file to view in the main viewer using the dropdown selector.

{% embed url="https://youtu.be/DtI_tOIjpnM" %}
{% endstep %}

{% step %}
### Use the main viewer

Use the main viewer to visualize the resampled files of the selected patient. Follow the collapsible information panels for mouse and keyboard controls related to the different visualization features.

{% embed url="https://youtu.be/hFYVMJaJGWY" %}
{% endstep %}

{% step %}
### Toggle the lesion mask overlay

Toggle the lesion mask overlay to analyze the selected lesion.

{% embed url="https://youtu.be/ghczW251ER8" %}
{% endstep %}

{% step %}
### Start Processing

Click the **Start Processing** button to generate the cropped files for each selected modality. Scroll down to see the generated cropped files in the second viewer once the loading bar has finished.

{% embed url="https://youtu.be/Obn4wGFhOx8" %}
{% endstep %}

{% step %}
### Use the second viewer

Use the second viewer to visualize the cropped files. It has the same mouse and keyboard controls as the main viewer for all visualization features.

{% embed url="https://youtu.be/qXXAISNPeqE" %}
{% endstep %}

{% step %}
### Start Analyzing

Click the **Start Analyzing** button to make an inference for the selected lesion. Scroll down to see the classification outcome results once loading has finished.

{% embed url="https://youtu.be/hjdNL7sM-kY" %}
{% endstep %}

{% step %}
### Toggle the heatmap overlay

Toggle the heatmap overlay to produce saliency maps showing the attention the model placed on all areas of the cropped lesion file to produce the classification outcome.

{% embed url="https://youtu.be/xG8uGrLI8lU" %}
{% endstep %}
{% endstepper %}
