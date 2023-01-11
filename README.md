## Html Page:
![image](/Screenshot%20from%202023-01-11%2013-28-37.png)

## Html and CSS code:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <style>
        {% comment %} Tag selector {% endcomment %}
            h1{
                color:green;
            }
            h2{
                color:red;
            }
            p{
                color:brown;
            }
            ul{
                color:orange;
            }
        {% comment %} Class selector {% endcomment %}
            .blue{
                color:blue;
            }
        {% comment %} id selector {% endcomment %}
            #magenta{
                color:magenta;
            }
        </style>
    </head>
    <body>
            <h1>Web Development Technologies </h1>
            <h2>Client Side UI Development</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Java Script</li>
                <li>React</li>
                <li>Angular</li>
                <li>Bootstrap</li>
            </ul> 
            <h2>Server Side Development</h2>
            <ul>
                <li>Django</li>
                <li>NodeJs</li>
                <li>Asp.net</li>
                <li>PHP</li>
                <li>Java Spring Framework</li>
            </ul>
            <h2>Database</h2>
            <ul class="blue">
                <li>SQLite</li>
                <li>MySQL</li>
                <li>Oracle</li>
                <li>SQL Server</li>
                <li>MongoDB</li>
            </ul>
            <h2>IDE/Editor</h2>
            <ul>
                <li id="magenta">Visual Studio Code</li>
                <li>Eclipse</li>
                <li>IntelliJ IDEA</li>
                <li>Eclipse Theia</li>
            </ul>
            <p>Designed by: AdhithiyanK</p>
    </body>
</html>

```
## 
