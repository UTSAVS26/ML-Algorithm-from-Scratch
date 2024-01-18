# Linear Regression
<hr>
<h2>What is Linear Regression?</h2>
Linear regression is a type of supervised machine learning algorithm that computes the linear relationship between a dependent variable and one or more independent features. When the number of the independent feature, is 1 then it is known as Univariate Linear regression, and in the case of more than one feature, it is known as multivariate linear regression.

<h2>Why Linear Regression is Important?</h2>
Linear regression is simple and easy to understand. It not only predicts but also serves as the basis for advanced models like regularization and support vector machines. It's crucial for checking if data meets certain assumptions in research.

<hr>
<h2>Types of Linear Regression</h2>
There are two main types of linear regression:
    <h2>Simple Linear Regression:</h2>
<p>This is the simplest form of linear regression, involving one independent variable and one dependent variable. The equation is:</p>
<p><code>y = &beta;<sub>0</sub> + &beta;<sub>1</sub>X</code></p>
<p>Where:</p>
<ul>
    <li><code>Y</code> is the dependent variable</li>
    <li><code>X</code> is the independent variable</li>
    <li><code>&beta;<sub>0</sub></code> is the intercept</li>
    <li><code>&beta;<sub>1</sub></code> is the slope</li>
</ul>

<h2>Multiple Linear Regression:</h2>
<p>This involves more than one independent variable and one dependent variable. The equation is:</p>
<p><code>y = &beta;<sub>0</sub> + &beta;<sub>1</sub>X<sub>1</sub> + &beta;<sub>2</sub>X<sub>2</sub> + ... + &beta;<sub>n</sub>X<sub>n</sub></code></p>
<p>Where:</p>
<ul>
    <li><code>Y</code> is the dependent variable</li>
    <li><code>X<sub>1</sub>, X<sub>2</sub>, ..., X<sub>p</sub></code> are the independent variables</li>
    <li><code>&beta;<sub>0</sub></code> is the intercept</li>
    <li><code>&beta;<sub>1</sub>, &beta;<sub>2</sub>, ..., &beta;<sub>n</sub></code> are the slopes</li>
</ul>

<h2>Other Regression Types:</h2>
<ol>
    <li><strong>Polynomial Regression:</strong> Incorporates higher-order polynomial terms into the model.</li>
    <li><strong>Ridge Regression:</strong> Prevents overfitting by introducing a penalty term to the least squares objective function.</li>
    <li><strong>Lasso Regression:</strong> Uses an L1 penalty term to shrink less important variable coefficients towards zero.</li>
    <li><strong>Elastic Net Regression:</strong> Combines penalties of ridge and lasso regression, offering a balance between their strengths.</li>
</ol>

<hr>
<h2>Applications of Linear Regression:</h2>
<p>Linear regression finds use in finance, economics, and psychology, predicting variables like stock prices, earnings, and currency values based on historical data.</p>

<h2>Advantages of Linear Regression:</h2>
<ul>
    <li>Simple and interpretable, revealing insights into variable relationships.</li>
    <li>Computationally efficient, suitable for large datasets and real-time applications.</li>
    <li>Relatively robust to outliers, providing stable model performance.</li>
    <li>Serves as a baseline model for comparison with more complex algorithms.</li>
    <li>Widely available in machine learning libraries with a rich history.</li>
</ul>

<h2>Disadvantages of Linear Regression:</h2>
<ul>
    <li>Assumes a linear relationship, impacting performance if the relationship is non-linear.</li>
    <li>Sensitive to multicollinearity, requiring caution with highly correlated variables.</li>
    <li>Requires features in a suitable form; feature engineering may be necessary.</li>
    <li>Susceptible to overfitting and underfitting, necessitating careful model tuning.</li>
    <li>Offers limited explanatory power for complex relationships, prompting the use of advanced techniques.</li>
</ul>
