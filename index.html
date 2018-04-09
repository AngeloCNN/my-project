<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <style>
        div.buttons {
            text-align: center;
            position: fixed;
            top: 128px;
            right: 100px;

        }

        div.buttons button {
            background-color: rgb(251, 201, 127);
            padding: 3px;
            margin: 7px;
            /*display:block;*/
            border-radius: 8px;
            /*box-shadow: 2.5px 2px 2px #00A5D2;*/
            /*border:#00A5D2 solid 2px;*/
        }
        /*#All_female__{
            fill:#FB8072;
        }*/
        /*.dimple-legend,.dimple-legend-key,.dimple-male{
            fill:#80B1D3;
        }
        .dimple-legend,.dimple-legend-key,.dimple-female{
            fill:#FB8072;
        }*/

        /*.dimple-female{
            fill:#FB8072;
        }
        .dimple-male{
            fill:#80B1D3;
        }*/


    </style>
    <script src="http://d3js.org/d3.v3.min.js" charset='utf-8'></script>
    <script src="http://dimplejs.org/dist/dimple.v2.0.0.min.js"></script>
    <script type="text/javascript">

//******************************************************************************************

    </script>
</head>

<body>
    <script type="text/javascript">
        var body = d3.select('body');
        //添加可视化标题
        d3.select('body')
            .append('h1')
            .style('text-align', 'center')
            .style('color', 'steelblue')
            .text('泰坦尼克号事件中游客生还率和各种因素的关系');
        
        //添加按钮，绑定按钮名称数据，添加按钮效果。
        var buttons = body.append('div')
            .attr('class', 'buttons')
            .selectAll('div')
            .data(['性别与生还率的关系', '船票等级与生还率的关系', '年龄与生还率的关系', '船票等级、性别与生还率的关系', '船票等级、年龄与生还率的关系', '性别、年龄与生还率的关系'])
            .enter()
            .append('div')
            .append('button')
            .style('cursor', 'pointer')
            .style('width', '100px')
            .style('height', '60px')
            .style('margin', '10px')
            .text(function (d) { return d });


        var width = 1500,
            height = 600;

        //在body标签中添加svg元素。
        var svg = d3.select("body")
            .append("svg")
            .attr("width", width)
            .attr("height", height)
            .append('g')
            .attr('class', 'chart');

        //画第一幅'性别与生还率的关系'图
        Sex_Survived_rate();

        //添加点击按钮后触发的绘制图表函数
        buttons.on("click", function (d) {
            d3.select(".buttons")
                .selectAll("button")
                .transition()
                .duration(100)
                .style("color", "black")
                .style("background", "rgb(251, 201, 127)");


            d3.select(this)
                .transition()
                .duration(100)
                .style("background", "#00A5D2")
                .style("color", "white");

            //点击按钮后先清除屏幕原有内容
            svg.selectAll('*').remove();
            
            //根据点击的按钮返回对应图表函数
            if (d === '性别与生还率的关系') {
                return Sex_Survived_rate();
            }
            else if (d === '船票等级与生还率的关系') {
                return Pclass_Survived_rate();
            }
            else if (d === '年龄与生还率的关系') {
                return Age_Survived_rate();
            }
            else if (d === '船票等级、性别与生还率的关系') {
                return Pclass_Sex_Survived_rate();
            }
            else if (d === '船票等级、年龄与生还率的关系') {
                return Pclass_Age_Survived_rate();
            }
            else if (d === '性别、年龄与生还率的关系') {
                return Sex_Age_Survived_rate();
            }
        })

        //**************************************************************************************************** 
        //下面是6个绘制图表的函数。                   
        function Sex_Survived_rate() {
            //debugger;
            d3.csv("Sex_Survived_rate_count.csv", function (data1) {
                var myChart = new dimple.chart(svg, data1);
                var x = myChart.addCategoryAxis("x", ['Sex']);
                myChart.addMeasureAxis("y", "Survived_rate");
                var s = myChart.addSeries('Passengers_count', dimple.plot.bar);
                //myChart.setBounds(380, 10, 800, 450)
                //myChart.addSeries(null, dimple.plot.scatter);
                //myChart.addSeries(null, dimple.plot.line);
                myChart.addLegend(660, 20, 200, 1000, "right");
                myChart.draw(600);
            })

        }
        function Pclass_Survived_rate() {
            d3.csv("Pclass_Survived_rate_count.csv", function (data2) {
                var myChart = new dimple.chart(svg, data2);
                var x = myChart.addCategoryAxis("x", ['Pclass']);
                myChart.addMeasureAxis("y", "Survived_rate");
                myChart.addSeries('Passengers_count', dimple.plot.bar);
                //myChart.setBounds(380, 10, 800, 450)
                //myChart.addSeries(null, dimple.plot.scatter);
                //myChart.addSeries(null, dimple.plot.line);
                myChart.addLegend(660, 20, 200, 1000, "right");
                myChart.draw(600);
            })
        }
        function Age_Survived_rate() {
            d3.csv('Age_Survived_rate_count.csv', function (data3) {
                var myChart = new dimple.chart(svg, data3);
                var x = myChart.addCategoryAxis("x", ['Age']);
                myChart.addMeasureAxis("y", "Survived_rate");
                myChart.addSeries('Passengers_count', dimple.plot.bar);
                //myChart.setBounds(380, 10, 800, 450)
                //myChart.addSeries(null, dimple.plot.scatter);
                //myChart.addSeries(null, dimple.plot.line);
                myChart.addLegend(660, 6, 200, 1000, "right");
                myChart.draw(600);
            })
        }
        function Pclass_Sex_Survived_rate() {
            d3.csv("Pclass_Sex_Survived_rate_count.csv", function (data4) {
                var myChart = new dimple.chart(svg, data4);
                var x = myChart.addCategoryAxis("x", ['Pclass', 'Sex','Passengers_count']);
                myChart.addMeasureAxis("y", "Survived_rate");
                myChart.addSeries('Sex', dimple.plot.bar);
                //myChart.setBounds(380, 10, 800, 450)
                //myChart.addSeries(null, dimple.plot.scatter);
                //myChart.addSeries(null, dimple.plot.line);
                myChart.addLegend(660, 20, 200, 1000, "right");
                myChart.draw(600);
                d3.select('svg')
                  .select('chart')
                  .select('#female_1')
                  .style('fill','red');
            })
        }
        function Pclass_Age_Survived_rate() {
            d3.csv("Pclass_Age_Survived_rate_count.csv", function (data5) {
                var myChart = new dimple.chart(svg, data5);
                var x = myChart.addCategoryAxis("x", ['Pclass', 'Age',"Passengers_count"]);
                myChart.addMeasureAxis("y", "Survived_rate");
                myChart.addSeries('Age', dimple.plot.bar);
                //myChart.setBounds(380, 10, 800, 450)
                //myChart.addSeries(null, dimple.plot.scatter);
                //myChart.addSeries(null, dimple.plot.line);
                myChart.addLegend(660, 20, 200, 1000, "right");
                myChart.draw(600);
            })
        }//"Sex_Age_Survived_rate.csv"
        function Sex_Age_Survived_rate() {
            d3.csv("Sex_Age_Survived_rate_count.csv", function (data5) {
                var myChart = new dimple.chart(svg, data5);
                var x = myChart.addCategoryAxis("x", ['Sex', 'Age', "Passengers_count"]);
                myChart.addMeasureAxis("y", "Survived_rate");
                myChart.addSeries('Age', dimple.plot.bar);
                //myChart.setBounds(380, 10, 800, 450)
                //myChart.addSeries(null, dimple.plot.scatter);
                //myChart.addSeries(null, dimple.plot.line);
                myChart.addLegend(660, 20, 200, 1000, "right");
                myChart.draw(600);
            })
        }
//*****************************************************************************************************   
    </script>
</body>

</html>
