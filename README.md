# My Portfolio
Некоторые примеры проектов по извлечению, обработке и презентации данных, выполненных по работе, а также просто из исследовательского интереса.

Some examples of projects on retrieving, analyzing and presenting data, which I fulfilled during my working expericence and as a hobby as well.

Tools
* **Python**: Pandas,
* **Tableau**

## Project 1: Scraping China's official statistics data
* Project for getting data about budget revenues and expenditures from monthly announcements posted on the official website of the Ministry of Finance of the PRC 

Further information: [IPython Notebook](https://github.com/dmplekhanov/Parsing_MOF_data/blob/master/MOF_parse.ipynb)

![](/images/Budget_income.png)

## Project 2: Dashboards in Tableau
* Central banks' communication practices are important for conducting efficent monetaty policy. The vizualization (in Russian language) tries to assess communication policy of the Bank of Russia by summarizing data on press releases published by the monetary authorities over the span of last 10+ years. [See in Tableau](https://public.tableau.com/app/profile/plekhanov/viz/CBR_communication/Dashboard1)

<div class='tableauPlaceholder' id='viz1622723802390' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CB&#47;CBR_communication&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CBR_communication&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CB&#47;CBR_communication&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div> 


## Project 3: Drawing maps with Tableau

<script src="https://www.example.com/javascripts/api/tableau-2.js"></script>
<div id="tableauViz"></div>

function initializeViz() {
var placeholderDiv = document.getElementById("tableauViz");
var url = "http://public.tableau.com/views/WorldIndicators/GDPpercapita";
var options = {
 width: '600px',
 height: '600px',
 hideTabs: true,
 hideToolbar: true,
 };
viz = new tableau.Viz(placeholderDiv, url, options);
}
