# Single patient

{% stepper %}
{% step %}
Click the **Demo Mode** button on the landing page. Select a pre-loaded demo patient using the dropdown button in the top-left corner of the page.

{% embed url="https://youtu.be/K0GaUql-EyM" %}
{% endstep %}

{% step %}
Select the desired lesion to run the auto-classification.

{% hint style="warning" %}
While multiple lesions for the same patient can be classified, this mode only allows one lesion to be processed at a time. If a new lesion for the same patient needs to be processed, it is **strongly recommended to reload the page** by pressing **Ctrl + F5** on the keyboard, or by clicking the refresh symbol in the browser.
{% endhint %}

{% embed url="https://youtu.be/jUsUDpvz3cs" %}
{% endstep %}

{% step %}
Select the desired channel configuration to run an inference using the dropdown button below the patient selector.

{% embed url="https://youtu.be/NYY0pi9sGIE" %}
{% endstep %}

{% step %}
Select the resampled file being viewed in the main viewer using the dropdown selector.

{% embed url="https://youtu.be/QToOYGtCHLc" %}
{% endstep %}

{% step %}
Use the main viewer to visualize the resampled files of the selected patient. Follow the collapsible information panels to find the related mouse and keyboard controls for the different visualization features.

{% embed url="https://youtu.be/BrwcAimYeGw" %}
{% endstep %}

{% step %}
Toggle the lesion mask overlay to analyze the selected lesion. Toggle **"Show in Grayscale"** to alternate between JET color scale and grayscale for applicable modalities.

{% embed url="https://youtu.be/2JCtOWIBOaw" %}
{% endstep %}

{% step %}
Click the **Start Processing** button to generate the cropped files for each of the selected modalities. Scroll down to see the generated cropped files in the second viewer once the loading bar has finished.

{% embed url="https://youtu.be/kemf89OmSZQ" %}
{% endstep %}

{% step %}
Use the second viewer to visualize the cropped files. It has the same mouse and keyboard controls as the main viewer. Toggle the **Sync** checkbox to view the same modality currently selected in the main viewer.

{% embed url="https://youtu.be/y6eon4auMu0" %}
{% endstep %}

{% step %}
Click the **Start Analyzing** button to make an inference for the selected lesion. Scroll down to see the classification outcome results once loading has finished.

{% embed url="https://youtu.be/-jga7LT3VB0" %}
{% endstep %}

{% step %}
Toggle the heatmap overlay to produce the saliency maps showing the attention the model placed on all areas of the cropped lesion file to produce the classification outcome.

{% embed url="https://youtu.be/vQl8wq5gOP8" %}
{% endstep %}
{% endstepper %}
