---
title: "My Hugo demo test"
date: 2021-05-10T15:12:37+08:00
draft: true
---

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>表格</title>
    <style type="text/css">
        *{
            margin: 0;
            padding: 0;
        }
        body{
            font: italic 20px Georgia, serif;
            letter-spacing: normal;
            background-color: #f0f0f0;
        }
        #content{
            width: 750px;
            padding: 40px;
            margin: 0 auto;
            background-color: #fff;
            border-left: 30px solid #1D81B6;
            border-right: 1px solid #ddd;
            box-shadow: 0px 0px 16px #aaa;
        }
        #table1{
            font: bold 16px/1.4em "Trebuchet MS", sans-serif;
        }
        #table1 thead th{
            padding: 15px;
            border: 1px solid #93CE37;
            border-bottom: 3px solid #9ED929;
            text-shadow: 1px 1px 1px #568F23;
            color: #fff;
            background-color: #9DD929;
            border-radius: 5px 5px 0px 0px;
        }
        #table1 thead th:empty{
            background-color: transparent;
            border: none;
        }
        #table1 tbody th{
            padding: 0px 10px;
            border: 1px solid #93CE37;
            border-right: 3px solid #9ED929;
            text-shadow: 1px 1px 1px #568F23;
            color: #666;
            background-color: #9DD929;
            border-radius: 5px 0px 0px 5px;
        }
        #table1 tbody td{
            padding: 10px;
            border: 2px solid #E7EFE0;
            text-align: center;
            text-shadow: 1px 1px 1px #fff;
            color: #666;
            background-color: #DEF3CA;
            border-radius: 2px;
        }
        #table1 tbody span.check::before{
            content: url(images/check0.png);
        }
        #table1 tfoot td{
            padding: 10px 0px;
            font-size: 32px;
            color: #9CD009;
            text-align: center;
            text-shadow: 1px 1px 1px #444;
        }
    </style>
</head>
<body>
<div id="content">
    <table id="table1">
        <thead>
            <tr>
                <th></th>
                <th scope="col" abbr="Starter">Smart Starter</th>
                <th scope="col" abbr="Medium">Smart Medium</th>
                <th scope="col" abbr="Business">Smart Business</th>
                <th scope="col" abbr="Deluxe">Smart Deluxe</th>
            </tr>
        </thead>
        <tfoot>
            <tr>
                <th scope="row">Price per month</th>
                <td>$ 2.90</td>
                <td>$ 5.90</td>
                <td>$ 9.90</td>
                <td>$ 14.90</td>
            </tr>
        </tfoot>
        <tbody>
            <tr>
                <th scope="row">Storage Space</th>
                <td>512MB</td>
                <td>1 GB</td>
                <td>2 GB</td>
                <td>4 GB</td>
            </tr>
            <tr>
                <th scope="row">Bandwidth</th>
                <td>50 GB</td>
                <td>100 GB</td>
                <td>150 GB</td>
                <td>unlimited</td>
            </tr>
            <tr>
                <th scope="row">Mysql Databases</th>
                <td>unlimited</td>
                <td>unlimited</td>
                <td>unlimited</td>
                <td>unlimited</td>
            </tr>
            <tr>
                <th scope="row">Setup</th>
                <td>12.90 ___FCKpd___0lt;/td>
                <td>12.90 ___FCKpd___0lt;/td>
                <td>free</td>
                <td>free</td>
            </tr>
            <tr>
                <th scope="row">PHP 5</th>
                <td><span class="check"></span></td>
                <td><span class="check"></span></td>
                <td><span class="check"></span></td>
                <td><span class="check"></span></td>
            </tr>
            <tr>
                <th scope="row">Ruby on Rails</th>
                <td><span class="check"></span></td>
                <td><span class="check"></span></td>
                <td><span class="check"></span></td>
                <td><span class="check"></span></td>
            </tr>
        </tbody>
    </table>
</div>
</body>
</html>
