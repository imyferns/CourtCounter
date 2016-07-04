# Court Counter
A simple Android app called Court Counter - the second project made as part of the Android Basics Nanodegree offered by Udacity. 

![courtcounter](https://cloud.githubusercontent.com/assets/4187068/16548371/d8d52cc6-4149-11e6-8d1e-82afe4f13bc8.png)


#How Court Counter is built
The app layout is constructed with a Relative Layout parent. The parent has a child horizontal Linear Layout which in turn has two child vertical Linear Layouts with equal weight to display each team as a column. The Reset Button is positioned at the bottom of the Relative Linear Layout. 

Appropriate Java methods are added and linked to the buttons. The scores are displayed in TextViews. The colours for the buttons and the Heading bar come from the styles.xml resource. 


#How to use Court Counter
Court Counter keeps track of the scores for two basketball teams, Team A and Team B. Each team's score is tracked separately. The user can add points for a 3 pointer, 2 pointer or a free throw. A Reset button resets both team's scores to 0. 


