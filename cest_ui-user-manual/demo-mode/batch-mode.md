# Batch mode

{% stepper %}
{% step %}
#### Click the **Batch Processing** button in the top-right corner of the demo page.

{% embed url="https://youtu.be/-Aa8VdwgGww" %}
{% endstep %}

{% step %}
#### Select or deselect patients to be processed for a batch run.

This can be done by toggling the checkbox next to the patient number, or by using the **Select All Patients** and **Deselect All** buttons. By default, all patients are selected.

{% embed url="https://youtu.be/Rcy6h60FrVo" %}
{% endstep %}

{% step %}
#### Select or deselect lesions to be processed for each patient in the batch run.

Expand the **Select Lesions** dropdown and toggle the checkbox next to each lesion, or use the **Select All** and **Deselect All** buttons. By default, all lesions are selected for each patient.

{% embed url="https://youtu.be/yWZs3RlEkwg" %}
{% endstep %}

{% step %}
#### Select or deselect channel configurations to be used to run inferences.

Expand the **Select Configuration** dropdown and toggle the desired configurations, or use the **Select All** and **Deselect All** buttons. By default, only the **6 Channels High Power** configuration is selected, as it is the recommended configuration.

{% embed url="https://youtu.be/dW_rWe57uKc" %}
{% endstep %}

{% step %}
#### Click the **Start Analyzing** button to start the batch run.

Wait until the loading bar reaches 100%. An Excel file will automatically be downloaded by your browser with the classification results for each selected patient and lesion. Results are also displayed in the _Outcome_ column of the table.

{% embed url="https://youtu.be/dv38KACrU5w" %}
{% endstep %}

{% step %}
#### Click the **View** button next to each patient row to view individual patient files in detail.

This button is disabled until an inference has been made.

{% embed url="https://youtu.be/huf_er_uxNU" %}
{% endstep %}

{% step %}
#### Once the view pop-up opens, it uses the same buttons and controls as Single Patient Mode.

Use the dropdown buttons to switch between resampled files and cropped lesion files, and between MRI modalities depending on your selected channel configuration.

{% embed url="https://youtu.be/tSuEPfZe6vQ" %}
{% endstep %}

{% step %}
#### Toggle the lesion overlay and heatmap overlay checkboxes to visualize the lesion mask and saliency attention maps on top of the resampled files and cropped files, respectively.

The checkbox automatically updates depending on your selection between resampled and cropped files in the dropdown menu.

{% embed url="https://youtu.be/MZl5gKiQi5Q" %}
{% endstep %}
{% endstepper %}
