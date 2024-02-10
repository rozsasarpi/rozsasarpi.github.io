---
title: "Overview"
permalink: /
excerpt: ""
---

I am experienced and deeply interested in data science, combining machine learning with first-principles-based modelling, and 
software development, alongside leadership within these domains. I am dedicated to applying my skills to address critical issues 
like climate change and sustainability.

<!-- Chart starts -->
<!-- todo: fix vertical alignment on small screens -->
<div id="myvenn" style="width: 100%;height:400px; float:center"></div>

<script type="text/javascript">
const symbolSize = 200;
const fontSize = 15;

var myVenn = echarts.init(document.getElementById('myvenn'));

var option = {
  xAxis: { min: -2, max: 2, show: false },
  yAxis: { min: -1, max: 2.5, show: false },
  series: [
    {
      symbolSize: symbolSize,
      data: [[0, 1.6]],
      type: 'scatter',
      color: '#7570b3',
      label: {
        formatter: 'data science \n (statistics and \n machine learning)',
        fontSize: fontSize,
        show: true
      }
    },
    {
      symbolSize: symbolSize,
      data: [[-0.6, 0]],
      type: 'scatter',
      color: '#1b9e77',
      label: {
        formatter: 'software development',
        fontSize: fontSize,
        show: true
      }
    },
    {
      symbolSize: symbolSize,
      data: [[0.6, 0]],
      type: 'scatter',
      color: '#d95f02',
      label: {
        formatter: 'engineering \n (natural sciences)',
        fontSize: fontSize,
        show: true
      }
    }
  ]
};

myVenn.setOption(option);
</script>

<!-- Chart ends -->

I have over 10 years of experience in applying statistics and risk analysis across various domains and more than 6 years of experience in machine learning, with a particular focus on time-series modeling.

My combined knowledge of data science (statistics and machine learning) and natural sciences (especially computational physics) enables me to solve a wide range of problems and to mathematically formulate problems where standard formulations and solutions do not exist.

For additional information see the other pages of this website and/or my [LinkedIn profile](https://www.linkedin.com/in/arpad-rozsas/).
