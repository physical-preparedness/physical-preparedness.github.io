---
layout: post
title: Does Body Weight Matter
---

The body weight is considered as an important measure of fitness and health in general by many people. The common opinion is that fit people have low body weight. In this post I used the scoreboards from TSC to find out, if the body weight is related to General Physical Preparedness.

<style>
.ct1 {
    background-color:  #ebfaeb;
}

.ct2 {
    background-color:  #adebad;
}

.ct3 {
    background-color:  #5cd65c;
}

.ct4 {
    background-color:  #29a329;
}

.ct2r {
    background-color:  #ff8080;
}

.ct1r {
    background-color:  #ffcccc;
}

.ct2b {background-color:  #66a3ff;}

.ct1b {background-color:  #cce0ff;}

</style>

The common opinion is that fit people have a low body weight. Probably the most known tool for recommendation of an optimal body weight is the BMI (body mass index). This index is calculated from weight and height of a person.
This tool is popular mainly among ordinary people with a low level of the GPP (General Physical Preparedness).
In contrary, the fitness community claims that the body weight measure even with a measure of a person's height does not provide any usefull information about the GPP.

As a data for my thoughts I used the scoreboards of the TSC (Tactical Strength Challenge). This event is considered as the best test of the GPP by many of elite coaches and sport instructors. Furthermore, there are no weight categories in the TSC, so this event can work well for this kind of study. 

If you care only about the conclusion and you do not want to know where it came from, then skip to the conclusion at the end of this post.


<h2>Never Heard about the Tactical Strength Challenge?</h2>
<p>
The TSC consists of three events in one day:
<ul>
    <li>max deadlift</li>
    <li>maximum number of pullups</li>
    <li>maximum repetitions of a kettlebell snatch in 5 minutes</li>
</ul>
As I mentioned before, <span class="emp">the TSC does not use any weight categories</span>.
The reason is an assumption, that the TSC is fair to everybody just by selection of the used events.
The maximal deadlift should be hard for the slim people.
And the heavy people should struggle with the pullups for repetitions.
In this post I also try to investigate, if these assumptions are correct.
For the purposes of this study the TSC results from fall 2014, spring 2015, fall 2015 and spring 2016 are used.
<span class="emp">The divisions used for the validations are just the novice division and the open division</span>.
The elite division is not used, because it contains only a small number of competitors.
Another problem is, that nobody can really say, if the distribution of the data is normal.
So in this case (small sample size, no information about distribution) it is not safe to use statistical tests.
</p>
<p>
Before we wil move to the data description, I have to mention something about the divisions according to the TSC rules:
<ul>
    <li>Men's Novice Division: snatch test with 20kg kettlebell</li>
    <li>Men's Open Division: snatch test with 24kg kettlebell</li>    
    <li>Women's Novice Division: snatch test with 12kg kettlebell, flexed arm hang instead of pullups</li>
    <li>Women's Open Division: snatch test with 16kg kettlebell</li>
</ul>
So according to the rules, <span class="emp">only the deadlift is really the same for all divisions</span>.
</p>


<h2>Common Body Weight for Fit People</h2>

<p>
The body weight statistical attributes for the divisions are displayed in the following table.
Persons without recorded body weight were removed from the data.
Used shortcuts and words in table stand for:
<ul>
    <li>The <span class="emp">Athletes</span> is amount of competitors.</li>
    <li>The <span class="emp">mean</span> stands for the arithmetic mean value.</li>
    <li>The <span class="emp">median</span> is the median value (most common value).</li>
    <li>The <span class="emp">std</span> is the standard deviation (how much the data vary).</li>
    <li>The <span class="emp">min</span> and <span class="emp">max</span> are the minimal and the maximal value.</li>
</ul>
</p>
<div class="regular_caption">Statistical attributes of the body weight in used data-set</div>

<table class="table table-stripped table-small">
    <thead>
    <tr>
        <th>Division</th>
        <th>Season</th>
        <th>Athletes</th>
        <th>mean [kg]</th>
        <th>median [kg]</th>
        <th>std [kg]</th>
        <th>min [kg]</th>
        <th>max [kg]</th>
    </tr>        
    </thead>
    <tbody>
<tr><td>Men's Open</td><td>Spring 2016</td><td>186</td><td>89.63</td><td>87.0</td><td>13.58</td><td>64.0</td><td>136.0</td></tr>
<tr><td>Men's Open</td><td>Fall 2015</td><td>156</td><td>91.07</td><td>88.0</td><td>13.8</td><td>64.0</td><td>138.0</td></tr>
<tr><td>Men's Open</td><td>Spring 2015</td><td>168</td><td>91.32</td><td>90.04</td><td>12.67</td><td>64.0</td><td>129.7</td></tr>
<tr><td>Men's Open</td><td>Fall 2014</td><td>120</td><td>88.86</td><td>87.36</td><td>12.55</td><td>63.0</td><td>140.6</td></tr>
<tr><td>Women's Open</td><td>Spring 2016</td><td>125</td><td>67.48</td><td>65.0</td><td>10.45</td><td>48.0</td><td>112.0</td></tr>
<tr><td>Women's Open</td><td>Fall 2015</td><td>100</td><td>67.33</td><td>65.0</td><td>10.26</td><td>49.0</td><td>103.0</td></tr>
<tr><td>Women's Open</td><td>Spring 2015</td><td>87</td><td>65.84</td><td>62.6</td><td>11.06</td><td>48.1</td><td>133.4</td></tr>
<tr><td>Women's Open</td><td>Fall 2014</td><td>71</td><td>65.19</td><td>63.5</td><td>10.22</td><td>48.1</td><td>117.9</td></tr>
<tr><td>Men's Novice</td><td>Spring 2016</td><td>197</td><td>85.74</td><td>83.0</td><td>14.62</td><td>48.0</td><td>143.0</td></tr>
<tr><td>Men's Novice</td><td>Fall 2015</td><td>150</td><td>86.83</td><td>85.0</td><td>13.12</td><td>62.0</td><td>126.0</td></tr>
<tr><td>Men's Novice</td><td>Spring 2015</td><td>157</td><td>86.26</td><td>83.55</td><td>14.32</td><td>61.2</td><td>133.8</td></tr>
<tr><td>Men's Novice</td><td>Fall 2014</td><td>120</td><td>84.64</td><td>82.19</td><td>14.68</td><td>49.9</td><td>134.7</td></tr>
<tr><td>Women's Novice</td><td>Spring 2016</td><td>311</td><td>70.12</td><td>66.0</td><td>14.33</td><td>42.0</td><td>117.0</td></tr>
<tr><td>Women's Novice</td><td>Fall 2015</td><td>240</td><td>70.16</td><td>68.0</td><td>14.0</td><td>41.0</td><td>143.0</td></tr>
<tr><td>Women's Novice</td><td>Spring 2015</td><td>238</td><td>69.93</td><td>67.11</td><td>14.41</td><td>25.9</td><td>136.1</td></tr>
<tr><td>Women's Novice</td><td>Fall 2014</td><td>142</td><td>70.15</td><td>67.81</td><td>12.75</td><td>46.7</td><td>112.0</td></tr>

    </tbody>
</table>

<p>
Now we can find out, whether the competitors of a division came from the same population in every season.
In other words, if they have similar mean value.
For this purpose the student t-test works well. See the following table.
In the table are shown the resulting p-values of the t-test. We can interpret it as:
<ul>
    <li>p=1.0 - both data-sets have an identical mean value</li>
    <li>p>0.05 - the mean values does not differ significantly</li>
    <li>p<0.05 - the mean values differ significantly</li>
    <li>The values were rounded, so the p=0.0 is not a zero, but it is really close to zero</li>
    <li><span class="emp">The more darker color the more similar mean value</span></li>
</ul>
</p>
<div class="regular_caption">Body weight T-test results for the single divisions</div>
<table class="table table-stripped table-small">
    <thead>
        <tr>
            <th></th>
            <th colspan="4">Men's Open</th>
            <th colspan="4">Women's Open</th>
            <th colspan="4">Men's Novice</th>
            <th colspan="4">Women's Novice</th>
        </tr> 
    </thead>
    <tbody>

<tr><td class="bold" rowspan="4">Men's<br>Open</td><td class="ct4">1.0</td><td class="ct3">0.33</td><td class="ct3">0.23</td><td class="ct3">0.62</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct2">0.01</td><td class="ct3">0.06</td><td class="ct2">0.03</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="ct3">0.33</td><td class="ct4">1.0</td><td class="ct3">0.87</td><td class="ct3">0.17</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct2">0.01</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="ct3">0.23</td><td class="ct3">0.87</td><td class="ct4">1.0</td><td class="ct3">0.1</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="ct3">0.62</td><td class="ct3">0.17</td><td class="ct3">0.1</td><td class="ct4">1.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.05</td><td class="ct3">0.2</td><td class="ct3">0.12</td><td class="ct2">0.02</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="bold" rowspan="4">Women's<br>Open</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct4">1.0</td><td class="ct3">0.91</td><td class="ct3">0.28</td><td class="ct3">0.14</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct2">0.03</td><td class="ct2">0.04</td><td class="ct3">0.05</td><td class="ct3">0.06</td></tr><tr><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.91</td><td class="ct4">1.0</td><td class="ct3">0.34</td><td class="ct3">0.18</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct2">0.03</td><td class="ct2">0.04</td><td class="ct2">0.04</td><td class="ct3">0.06</td></tr><tr><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.28</td><td class="ct3">0.34</td><td class="ct4">1.0</td><td class="ct3">0.7</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct2">0.01</td></tr><tr><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.14</td><td class="ct3">0.18</td><td class="ct3">0.7</td><td class="ct4">1.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="bold" rowspan="4">Men's<br>Novice</td><td class="ct2">0.01</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.05</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct4">1.0</td><td class="ct3">0.47</td><td class="ct3">0.74</td><td class="ct3">0.52</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="ct3">0.06</td><td class="ct2">0.01</td><td class="ct1">0.0</td><td class="ct3">0.2</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.47</td><td class="ct4">1.0</td><td class="ct3">0.71</td><td class="ct3">0.2</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="ct2">0.03</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.12</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.74</td><td class="ct3">0.71</td><td class="ct4">1.0</td><td class="ct3">0.36</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct2">0.02</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.52</td><td class="ct3">0.2</td><td class="ct3">0.36</td><td class="ct4">1.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td></tr><tr><td class="bold" rowspan="4">Women's<br>Novice</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.06</td><td class="ct3">0.07</td><td class="ct2">0.01</td><td class="ct2">0.01</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct4">1.0</td><td class="ct3">0.97</td><td class="ct4">1.0</td><td class="ct3">0.99</td></tr><tr><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.06</td><td class="ct3">0.07</td><td class="ct2">0.01</td><td class="ct2">0.01</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.97</td><td class="ct4">1.0</td><td class="ct3">0.97</td><td class="ct3">0.99</td></tr><tr><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.07</td><td class="ct3">0.08</td><td class="ct2">0.01</td><td class="ct2">0.01</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct4">1.0</td><td class="ct3">0.97</td><td class="ct4">1.0</td><td class="ct3">0.98</td></tr><tr><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.07</td><td class="ct3">0.07</td><td class="ct2">0.01</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct1">0.0</td><td class="ct3">0.99</td><td class="ct3">0.99</td><td class="ct3">0.98</td><td class="ct4">1.0</td></tr>

    </tbody>
</table>
<p>
From the above figure, we can read some interesting points:
<ul class="emp_result">
    <li>Every division has own population of competitors, and this population is significantly different from other division populations.</li>
    <li>The mean value of such a division population does not change from season to season significantly.</li>
</ul>
</p>



<h2>Body Weight Influence on a Performance</h2>
<p>
In the following table are displayed the <span class="emp">correlation coefficients of the body weight and results</span> from the individual events. If you do not remember what the correlation coefficient <span class="emp">r</span> is, then read:
<ul>
    <li><span class="emp">r</span> close to 1 means that data-sets are directly related</li>
    <li>If the value is close to 0, then the data-sets are not related at all.</li>
    <li>If the value is close to -1, then the data-sets are indirectly related (if one series is increasing, the second series is decreasing)</li>
</ul>
And for the <span class="emp">p</span> value stands the same rules like before:
<ul>
    <li>p>0.05 - the correlation is not significant</li>
    <li>p<0.05 - the correlation is significant</li>
</ul>
</p>
<div class="regular_caption">Correlation coefficients of the body weight and results of the events</div>
<table class="table table-stripped table-small">
    <thead>
    <tr>
        <th colspan="2"></th>
        <th colspan="2">Deadlift</th>
        <th colspan="2">Pullup</th>
        <th colspan="2">Snatch</th>
    </tr> 
    <tr>
        <th>Division</th>
        <th>Season</th>
        <th>r</th>
        <th>p</th>
        <th>r</th>
        <th>p</th>
        <th>r</th>
        <th>p</th>
    </tr>        
    </thead>
    <tbody>

<tr><td>Men's Open</td><td>Spring 2016</td><td>0.374</td><td>1.5E-7</td><td>-0.549</td><td>4.9E-16</td><td>0.047</td><td>5.2E-1</td></tr>
<tr><td>Men's Open</td><td>Fall 2015</td><td>0.401</td><td>2.2E-7</td><td>-0.578</td><td>2.7E-15</td><td>-0.07</td><td>3.9E-1</td></tr>
<tr><td>Men's Open</td><td>Spring 2015</td><td>0.344</td><td>5.0E-6</td><td>-0.516</td><td>7.8E-13</td><td>-0.05</td><td>5.2E-1</td></tr>
<tr><td>Men's Open</td><td>Fall 2014</td><td>0.46</td><td>1.3E-7</td><td>-0.522</td><td>1.0E-9</td><td>-0.008</td><td>9.3E-1</td></tr>
<tr><td>Women's Open</td><td>Spring 2016</td><td>0.414</td><td>1.6E-6</td><td>-0.472</td><td>2.8E-8</td><td>0.153</td><td>8.9E-2</td></tr>
<tr><td>Women's Open</td><td>Fall 2015</td><td>0.451</td><td>2.5E-6</td><td>-0.481</td><td>4.1E-7</td><td>0.021</td><td>8.4E-1</td></tr>
<tr><td>Women's Open</td><td>Spring 2015</td><td>0.295</td><td>5.6E-3</td><td>-0.3</td><td>4.8E-3</td><td>-0.041</td><td>7.1E-1</td></tr>
<tr><td>Women's Open</td><td>Fall 2014</td><td>0.31</td><td>8.5E-3</td><td>-0.335</td><td>4.3E-3</td><td>0.262</td><td>2.7E-2</td></tr>
<tr><td>Men's Novice</td><td>Spring 2016</td><td>0.501</td><td>6.6E-14</td><td>-0.483</td><td>6.2E-13</td><td>0.048</td><td>5.0E-1</td></tr>
<tr><td>Men's Novice</td><td>Fall 2015</td><td>0.418</td><td>1.0E-7</td><td>-0.469</td><td>1.5E-9</td><td>0.226</td><td>5.5E-3</td></tr>
<tr><td>Men's Novice</td><td>Spring 2015</td><td>0.325</td><td>3.4E-5</td><td>-0.59</td><td>4.5E-16</td><td>-0.007</td><td>9.3E-1</td></tr>
<tr><td>Men's Novice</td><td>Fall 2014</td><td>0.331</td><td>2.2E-4</td><td>-0.466</td><td>8.0E-8</td><td>0.133</td><td>1.5E-1</td></tr>
<tr><td>Women's Novice</td><td>Spring 2016</td><td>0.387</td><td>1.4E-12</td><td>-0.704</td><td>8.2E-48</td><td>0.027</td><td>6.3E-1</td></tr>
<tr><td>Women's Novice</td><td>Fall 2015</td><td>0.357</td><td>1.2E-8</td><td>-0.673</td><td>4.7E-33</td><td>-0.06</td><td>3.5E-1</td></tr>
<tr><td>Women's Novice</td><td>Spring 2015</td><td>0.497</td><td>3.0E-16</td><td>-0.651</td><td>4.9E-30</td><td>0.085</td><td>1.9E-1</td></tr>
<tr><td>Women's Novice</td><td>Fall 2014</td><td>0.4</td><td>8.1E-7</td><td>-0.59</td><td>1.1E-14</td><td>0.037</td><td>6.6E-1</td></tr>


    </tbody>
</table>

<p>
With this knowledge, we can conclude some results. And the results are pretty much as everybody expected:
<ul class="emp_result">
    <li>Heavy people can deadlift heavier weights.</li>
    <li>Leaner (not so heavy) people can do more repetitions of pullups.</li>
    <li>The result of snatch test is not significantly related to the body weight.</li>
</ul>
</p>

<p>
It is also possible to put the results in figures.
To emphasize what you should see there, I also put there two regression curves.
</p>

<div class="regular_caption">Relation between the body weight and the maximal deadlift</div>
<img class="regular_image" src="/images/bw1/bodyweight_deadlift.png" alt="Body weight relation with maximal deadlift">   
<div class="regular_caption">Relation between the body weight and the pullup performance</div>
<img class="regular_image" src="/images/bw1/bodyweight_pullup.png" alt="Body weight relation with pullup performance">
<div class="regular_caption">Relation between the body weight and the snatch performance</div>
<img class="regular_image" src="/images/bw1/bodyweight_snatch.png" alt="Body weight relation with snatch performance">  



<h2>Body Weight Influence on Final TSC Rank</h2>
<p>
The comparison of the best 10% of competitors of all seasons (according to ranking) with rest of the competitors is in the following table.
The p-value represents how significant (reliable) is the differences between mean values.
</p>
<div class="regular_caption">Correlation coefficients comparison between the best 10% competitors and the rest</div>
<table class="table table-stripped table-small">
<thead>
    <tr>
        <th>Division</th>
        <th>Athletes</th>
        <th>min [kg] <br> of top 10%</th>
        <th>max [kg] <br> of top 10%</th>
        <th>mean value [kg] <br> of top 10%</th>
        <th>mean value [kg] <br> of the rest</th>
        <th>p</th>
    </tr>
</thead>
<tbody>
<tr><td>Men's Open</td><td>601</td><td>65.0</td><td>105.0</td><td>88.0</td><td>90.4</td><td>0.054</td></tr>
<tr><td>Men's Novice</td><td>577</td><td>60.8</td><td>116.7</td><td>86.7</td><td>86.0</td><td>0.647</td></tr>
<tr><td>Women's Open</td><td>366</td><td>53.0</td><td>79.0</td><td>65.8</td><td>66.5</td><td>0.551</td></tr>
<tr><td>Women's Novice</td><td>891</td><td>46.7</td><td>89.0</td><td>65.7</td><td>70.5</td><td>0.0</td></tr>
</tbody>
</table>
<p>
According to the p-values and the mean-values from the table above, we can point out something about the best 10% of competitors:
<ul>
    <li>Top 10% has probably the same mean value of the body weight as the rest in the men's open division</li>
    <li>Top 10% has the same mean value of the body weight as the rest in the Men's novice division and the women's open division</li>
    <li>Top 10% has significantly different mean value of the body weight than the rest in the women's novice division</li>
</ul> 
</p>


<h2>Conclusion</h2>
<p>
So it really seems that the body weight without further information (body composition, etc.)
does not say too much about overall fitness of a person.
</p>
<p>
Few interesting points to remember:
<ul class="emp_result">
    <li>Heavier people have an advantage in absolute strength (according to the deadlift results).</li>
    <li>Body weight decrease can help with relative strength (according to the pullup results)</li>
    <li>The cardio-vascular endurance seems to be independent of the body weight,
    even if the body weight works partially as a load of the tested exercise (snatches).</li>
    <li>The best competitors in the women's novice division have significantly lower body weight than is average in their division.</li>
    <li>The TSC seems to be fair competition even without the weight categories.</li>
</ul>
I believe that for most of you the above points are not surprising.
This is nice thing in the world where "the shocking new truths" are appearing every second.
</p>
