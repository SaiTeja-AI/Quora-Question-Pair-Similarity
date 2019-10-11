# Quora Question Pair Similarity
<p>we all know quora is a place where we can gain and share knowledge about any thing.It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.</p>
<p>Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.</p>
<h3>Problem Statement: </h3>
<p>Identify which questions asked on Quora are duplicates of questions that have already been asked.</p>
<h3>1.3 Real world/Business Objectives and Constraints</h3>
<ul>
  <li> The cost of a mis-classification can be very high.</li>
  <li> You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.</li>
  <li> No strict latency concerns.</li>
  <li> Interpretability is partially important.</li>
</ul>
<h3> Performance Metrics </h3>
<ul>
  <li> log-loss </li>
  <li> Binary Confusion Matrix </li>
</ul>
<h3> Data OverView and Exploratory Data Analysis </h3>
<ul>
  <li> Data will be in a file Train.csv </li>
  <li> Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate </li>
  <li> Number of rows in Train.csv = 404,290 </li>
</ul>
<h3> Some Analysis: </h3>
<ul>
  <li> Distribution of data points among output classes. </li>
  <img src="img1.png"></img>
  
