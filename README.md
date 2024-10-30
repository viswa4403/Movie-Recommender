<h2>MOVIE RECOMMENDATION SYSTEM</h2>

<body>

<p>Welcome to the <strong>Movie Recommendation System</strong> project! This system is designed to help users discover movies they love by leveraging data-driven recommendations. We have built this as a comprehensive solution that includes collaborative and content-based filtering to suggest movies based on a user’s preferences and the movies’ features.</p>

<h2>Project Motivation</h2>

<p>Creating this project allowed us to explore how recommendation engines work under the hood and how they utilize complex datasets to deliver personalized suggestions. Our goal was to implement a system that effectively balances user tastes with movie attributes, making it a dynamic and enjoyable way to find new films.</p>

<h2>Dataset</h2>

<p>The dataset we have used in this project:</p>
<ul>
    <li><a href="https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata">TMDB Dataset</a><br></li>
  <li><a href="https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset">Movie Dataset</a></li>
</ul>

<h2>Key Features</h2>
<ul>
    <li><strong>Collaborative Filtering</strong>: This part of the system makes recommendations by analyzing user behaviors and interactions. It’s particularly useful for recommending popular movies that similar users have enjoyed.</li>
    <li><strong>Content-Based Filtering</strong>: The model considers movie metadata, like genres, actors, and directors, allowing for recommendations based on movie content itself. This is especially helpful when recommending similar movies that match the user’s viewing history.</li>
    <li><strong>Hybrid Model</strong>: We have combined both approaches to create a hybrid model that delivers more personalized and accurate recommendations, giving users a more tailored experience.</li>
</ul>
<h2>Setup Instructions</h2>

<p>To run this project, follow these steps:</p>
<ol>
    <li><strong>Clone the repository</strong>:
        <pre><code>git clone https://github.com/yourusername/Movie-Recommendation-System.git</code></pre>
    </li>
    <li><strong>Install necessary packages</strong>:
        <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li><strong>Download and place the dataset</strong>:<br>
        Download the Movies Dataset from Kaggle and store it in a folder named <code>data/</code> in the root project directory.
    </li>
</ol>

<h2>How to Use</h2>

<ol>
    <li><strong>Data Preprocessing</strong>: The notebook guides you through cleaning and preparing the dataset to ensure efficient processing and better recommendations.</li>
    <li><strong>Training the Model</strong>: Choose between collaborative, content-based, or hybrid approaches, and then train the model. Each approach offers unique insights and recommendation styles.</li>
    <li><strong>Generating Recommendations</strong>: Run the final prediction code, and the system will generate personalized movie suggestions based on user input or previous interactions.</li>
</ol>

<h2>Results</h2>

<p>We have evaluated the recommendation system’s performance using metrics such as RMSE and Precision to ensure it accurately reflects user preferences. The results showed promising alignment with user tastes, confirming that the model can make reliable recommendations.</p>

<h2>Team Members</h2>
<ul>
    <li><strong>Abhijit P A</strong> - CB.EN.U4CSE21101</li>
    <li><strong>Hariish G</strong> - CB.EN.U4CSE21124</li>
    <li><strong>Kamalesh L</strong> - CB.EN.U4CSE21127</li>
    <li><strong>Viswa A V</strong> - CB.EN.U4CSE21168</li>
</ul>
  
</body>

