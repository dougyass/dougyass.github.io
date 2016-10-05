<h1>Billboard Top 100 Data Analysis</h1>

<img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Billboard_Hot_100_logo.jpg" border="0" alt="BillBoard">

<h2>Problem Statement and Hypothesis</h2>
<p>Do songs that improve less than 10 spots their 1st week on the top 100 peak faster?</p>

<h2>Risks and Assumptions</h2>
<p>The data analysis was performed based on a sample of 317 songs in the year 2000 that were on the Billboard top 100. We are assuming that these are the only 317 songs that were on the list and this is a full sample for the year 2000. After looking through the data, a couple of errors popped out. First, "Rock'n'Roll" and "Rock" were treated as two separate genres. Also "R&B" was sometimes listed as "R  &  B". Given these two minor errors, we can't be 100% confident that there aren't other similar errors in the dataset. </p>

<h2>Data Analysis</h2>
<p>After cleaning the data, I searched for any interesting trends. I saw that 'Rock' had the most Billboard Top 100 hits with 137 of the 317 songs followed by Country (74), Rap (58), R&B (23), Pop (9), Latin (9), Electronica (4), Gospel (1), Jazz (1), and Reggae (1). My primary focus was trying to see if any variables in the dataset could help predict how long it takes for a song to peak. Below is a visualization of "Average Days to Peak by Genre".

<img src="http://i64.tinypic.com/16k2hz5.png">

<p>It appears that Jazz peaks quickly in comparison to other genres but there is only one Jazz song in the dataset so there is no strong conclusion to be drawn there. Of the top 4 Genres R&B and Rap appear to peak about two weeks faster than Rock and Country. I also examined if there was a relationship between what spot a song enters the Billboard Top 100 compared to how long it takes to peak, which can be seen below</p>

<img src="http://i63.tinypic.com/jt76z6.png">

<p>There does not appear to be any strong relationship between spot entered and peak time. The only thing that stood out from eyeballing the data was that songs that entered the top 100 in the low 80's had longer peak times, but that was only a couple of data points. I also investigated if the length of the song correlated with peak time as seen below. </p>

<img src="http://i64.tinypic.com/2mgo853.png">

<p>Again, there didn't seem to be much of a correlation between the length of the song and how long it took to peak. There were some high peak times for songs in the 275-300 seconds range, but they appeared to be outliers.</p>

<h2>Evaluating Findings</h2>
<img src="http://i67.tinypic.com/2vjomkh.png">
<p>After examining the data I found the most interesting correlation to be between increase in week 1 spot compared to peak time. To test my hypothesis - Do songs that improve less than 10 spots their 1st week on the top 100 peak faster? - I calculated the t-statistic associated with the hypothesis.</p>

<p>The sample I was testing was songs that improved less than 10 spots from week 1 to week 2. That sample of 189 songs had a mean of 47.74 and a standard deviation of 41.57. The standard error was 3.02 which ultimately gave us a t-statistic of -1.49. That converted to a p-value gave us 0.1379, which is higher than the threshold of 0.05. Since the p-value is higher than 0.05 we fail to reject the null hypothesis and cannot accept the alternative hypothesis. </p>








