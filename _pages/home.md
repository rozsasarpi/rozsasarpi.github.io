---
title: "Overview"
permalink: /
excerpt: ""
---

I am highly interested in:
- data science,
- combination of machine learning and physics,
- software development,
- leadership in engineering and sciences,
- **and above all, in applying my skills to relevant social and environmental issues such as climate change and sustainability**.

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
        formatter: 'engineering \n (natural science)',
        fontSize: fontSize,
        show: true
      }
    }
  ]
};

myVenn.setOption(option);
</script>

<!-- Chart ends -->

I was trained as a civil engineer (PhD) and have more than 10 years of experience in applying statistics and risk analysis to civil engineering problems and beyond, and more than 4 years of experience with artificial intelligence (if we exclude the plenty of statistical models and approaches "expropriated" by the field of AI from statistics).

My combined knowledge of data science (statistics and machine learning) and natural sciences (particularly computational physics) allows me to solve a wide range of problems and to mathematically formulate problems where no standard formulation and solution are available.

For additional information see the other pages of this website and/or my [LinkedIn profile](https://www.linkedin.com/in/arpad-rozsas/).
