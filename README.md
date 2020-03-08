<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>

        header, main, footer {
            width: 700px;
            margin: 0 auto;
        }

        /* 设置头部 */
        header {
            height: 150px;
            background-color: silver;
        }

        /* 设置主体 */
        main {
            height: 500px;
            background-color: #bfa;
            margin: 10px auto;
        }

        nav, article, aside{
            float: left;
            height: 100%;
        }

        /* 设置左侧的导航 */
        nav {
            width: 200px;
            background-color: grey;
            height:50%;
            position: relative;
            /*display: flex;
            align-items: flex-end;*/
        }
        
        
        /* 设置中间的内容 */
        article {
            width: 280px;
            background-color: orange;
            margin: 0 10px;
            position: relative;
        }

        /* 设置右侧的内容 */
        aside {
            width: 200px;
            background-color: pink;
            height: 50%;
            position: relative;
        }

        /* 设置底部 */
        footer {
            height: 150px;
            background-color: tomato;
        }
        .nf1 {
            height: 50px;
            width: 200px;
            background-color: #FF3;
            position: absolute;
            top: 253px;
            left: 0px;
        }
        .nf2 {
            height: 50px;
            width: 200px;
            background-color: #FF3;
            position: absolute;
            top: 253px;
            left: 0px;
    </style>
</head>
<body>

    <!-- 创建头部 -->
    <header></header>

    <!-- 创建网页的主体 -->
    <main>
        <!-- 左侧导航 -->
       <nav>  
             <div class="nf1"><a href="affordance.html">affordance</a>

               <p><a href="historical development.html">historical development</a></p>
                 </div>
             

       </nav>
       
    
       <!-- 中间的内容 -->
       <article>
          
       </article>

       <!-- 右边的边栏 -->
       <aside>
        <div class="nf2"><a href="Grid.html">contraints</a>.</p>

                <p><a href="artvive.html">artvive</a></p>
            </div>
             
         </aside>
       </aside>

    </main>
    
    <!-- 网页的底部 -->
    <footer></footer>
</body>
</html>
