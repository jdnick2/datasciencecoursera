<h2>Explanation of Files Used</h2>
<ul>
<li><code>activity_labels.txt</code> - Lists each activity with ID.</li>
<li><code>features.txt</code> - List of the 561 features.</li>
<li><code>subject_test.txt</code> - Vector of 2947 integers, showing the volunteer ID related to the observations in <code>X_test.txt</code>.</li>
<li><code>subject_train.txt</code> - Vector of 7352 integers, showing the volunteer ID related to the observations in <code>X_train.txt</code>.</li>
<li><code>X_test.txt</code> - 2947 observations of the 561 features, for 9 of the 30 volunteers.</li>
<li><code>X_train.txt</code> - 7352 observations of the 561 features, for 21 of the 30 volunteers.</li>
<li><code>y_test.txt</code> - A vector of 2947 integers, showing the activity ID related to the observations in <code>X_test.txt</code>.</li>
<li><code>y_train.txt</code> - A vector of 7352 integers, showing the activity ID related to the observations in <code>X_train.txt</code>.</li>
</ul>

<h2>Cleaning the Data</h2>
<ol>
<li>Setup - Data gets retrieved and unzipped, necessary packages get installed.</li>
<li>Read in data.</li>
<li>Remove data that doesn't contain the string <code>mean</code> or <code>std</code>.</li>
<li>Tidy data table is created with the mean of each feature for each subject and activity. Each subject has a row for each of the activities, and each of these rows contain the means for each of the features.</li>
<li>Tidy data set gets output to <code>tidy_data.txt</code>.</li>
</ol>