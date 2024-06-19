---
hide:
  - toc
  - navigation
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <title>Markdown with Sidebar</title> -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
        }
        #sidebar {
            width: 200px;
            padding: 15px;
            background: none;
            position: fixed;  /* 侧边栏固定 */
            height: 100%;  /* 高度为100% */
            overflow-y: auto;  /* 如果内容过长，允许滚动 */
        }
        #content {
            margin-left: 220px;  /* 确保内容部分不与侧边栏重叠 */
            padding: 15px;
            flex-grow: 1;  /* 确保内容部分占据剩余空间 */
        }
        #sidebar a {
            display: block;
            color: #000;
            padding: 5px 0;  /* 调整上下间距 */
            text-decoration: none;
        }
        #sidebar a:hover {
            background: none;  /* 鼠标悬停时不变色 */
        }
        h2 {
            margin-top: 50px;
        }
    </style>
</head>
<body>

<div id="sidebar">
    <a href="#section1">Biography</a>
    <a href="#section2">Education Background</a>
    <a href="#section3">Selected Publications</a>
</div>

<div id="content">
    <h1><strong>Principal Investigator</strong></h1>
    <div align="center">
        <img src="../assets/images/members/director.png" style="width: 20%">
        <br>
        <div style="font-weight: bold;">Prof. Simon Pun, Dean of Harmonia College</div>
    </div>

    <h2 id="section1"><strong>Biography</strong></h2>
    <p>Prof. Pun received the B.Eng. degree in electronic engineering from The Chinese University of Hong Kong (CUHK) in 1996, the M.Eng. degree in computer science from the University of Tsukuba, Tsukuba, Japan, in 1999, and the Ph.D. degree in electrical engineering from the University of Southern California (USC), Los Angeles, CA, USA, in 2006. He was a Post-Doctoral Research Associate with Princeton University, Princeton, NJ, USA, from 2006 to 2008.</p>

    <p>Prior to joining CUHK(SZ) in 2015, Prof. Simon Pun held research positions at Huawei (USA), Mitsubishi Electric (Boston) and Sony (Tokyo). He has led multimillion-dollar channel measurement/modeling projects for LTE femto cells, Japanese high-speed bullet trains and most recently, multi-polarized LTE macro and small cells. His current research is funded by the Ministry of Science and Technology of China, the National Natural Science Foundation of China, the Shenzhen Science and Technology Innovation and Huawei Technologies. He is the vice-director of the Shenzhen Key Laboratory of IoT Intelligent Systems and Wireless Network Technology and the director of a few joint research labs including the CUHK(SZ) - DeRUCCI Joint Laboratory of Smart Home Technology established in 2022.</p>

    <p>Prof. Pun has published more than 120 technical publications. He also holds 12 granted patents including LTE essential patents. Among his publications, his book entitled “Multi-Carrier Techniques for Broadband Wireless Communications” is collected by 2000 libraries worldwide including the M.I.T. library. Dr. Pun has received three prestigious best paper awards including IEEE VTC'06 Fall, IEEE ICC'08 and IEEE Infocom'09.</p>

    <p>Prof. Pun served as associate editor in the channel modeling track for the IEEE Transactions on Wireless Communications in 2010 - 2014. He has chaired the 31st Wireless and Optical Communications Conference (WOCC), Shenzhen in 2022.8 and co-chaired the Wireless Communications Symposium (WCS) for ICC'2012 and ICC'2020, one of the two flagship conferences organized by the IEEE ComSoc. Dr. Pun is a senior member of IEEE. He is the founding chair of the IEEE Shenzhen Joint ComSoc-SPS Chapter.</p>

    <p>At CUHKSZ, Professor Pun has served as the assistant dean (student affairs) for the School of Science and Engineering (2015-2019), the director for the Nobel Class (the elite class of the University) since 2018, the acting college master for Muse College (2016-2017), and the associate college master for Harmonia College (since 2020), the Assembly Fellow of Diligentia College (since 2016), the founding director of the Undergraduate Student Teaching Fellow (USTF) program (since 2016), the Program Coordinator for the Electronic and Information Engineering (EIE) (2015-2022) and the vice-director of the Maker Lab (since 2019).</p>

    <h2 id="section2"><strong>Education Background</strong></h2>
    <ul>
        <li><strong>2006-2008</strong>, Postdoctoral Fellow, <em>Princeton University</em>, U.S.A</li>
        <li><strong>2006</strong>, Doctor of Philosophy, <em>University of Southern California</em>, U.S.A</li>
        <li><strong>1999</strong>, Master of Engineering, <em>University of Tsukuba</em>, Japan</li>
        <li><strong>1996</strong>, Bachelor of Engineering, <em>The Chinese University of Hong Kong</em>, Hong Kong</li>
    </ul>

    <h2 id="section3"><strong>Selected Publications</strong></h2>
    <ul>
        <li>M.O. Pun, M. Morelli and C.-C. Kuo, Multi-Carrier Techniques For Broadband Wireless Communications: A Signal Processing Perspectives, Imperial College Press, U.K. 2007. <a href="https://books.google.co.uk/books?hl=zh-CN&lr=&id=zl-7CgAAQBAJ&oi=fnd&pg=PR7&dq=Multi-Carrier+Techniques+For+Broadband+Wireless+Communications&ots=E4D4_xRom-&sig=ObnyBEVO-U-k55MAIr3DG2Dqv5A">[Book Link]</a></li>
    </ul>
</div>

</body>
</html>



<!-- # **Principal Investigator**

<div align=center>
<img src='../assets/images/members/director.png' style="width: 20%">
<br>
<div style="font-weight: bold;">Prof. Simon Pun, Dean of Harmonia College</div>
</div>

## **Biography**

Prof. Pun received the B.Eng. degree in electronic engineering from The Chinese University of Hong Kong (CUHK) in 1996, the M.Eng. degree in computer science from the University of Tsukuba, Tsukuba, Japan, in 1999, and the Ph.D. degree in electrical engineering from the University of Southern California (USC), Los Angeles, Los Angeles, CA, USA, in 2006. He was a Post-Doctoral Research Associate with Princeton University, Princeton, NJ, USA, from 2006 to 2008.

Prior to joining CUHK(SZ) in 2015, Prof. Simon Pun held research positions at Huawei (USA), Mitsubishi Electric (Boston) and Sony (Tokyo). He has led multimillion-dollar channel measurement/modeling projects for LTE femto cells, Japanese high-speed bullet trains and most recently, multi-polarized LTE macro and small cells. His current research is funded by the Ministry of Science and Technology of China, the National Natural Science Foundation of China, the Shenzhen Science and Technology Innovation and Huawei Technologies. He is the vice-director of the Shenzhen Key Laboratory of IoT Intelligent Systems and Wireless Network Technology and the director of a few joint research labs including the CUHK(SZ) - DeRUCCI Joint Laboratory of Smart Home Technology established in 2022.

Prof. Pun has published more than 120 technical publications. He also holds 12 granted patents including LTE essential patents. Among his publications, his book entitled “Multi-Carrier Techniques for Broadband Wireless Communications” is collected by 2000 libraries worldwide including the M.I.T. library. Dr. Pun has received three prestigious best paper awards including IEEE VTC'06 Fall, IEEE ICC'08 and IEEE Infocom'09.

Prof. Pun served as associate editor in the channel modeling track for the IEEE Transactions on Wireless Communications in 2010 - 2014. He has chaired the 31st Wireless and Optical Communications Conference (WOCC), Shenzhen in 2022.8 and co-chaired the Wireless Communicaitons Symposium (WCS) for ICC'2012 and ICC'2020, one of the two flagship conferences organized by the IEEE ComSoc. Dr. Pun is a senior member of IEEE. He is the founding chair of the IEEE Shenzhen Joint ComSoc-SPS Chapter.

At CUHKSZ, Professor Pun has served as the assistant dean (student affairs) for the School of Science and Engineering (2015-2019), the director for the Nobel Class (the elite class of the University) since 2018, the acting college master for Muse College (2016-2017), and the associate college master for Harmonia College (since 2020), the Assembly Fellow of Diligentia College (since 2016), the founding director of the Undergraduate Student Teaching Fellow (USTF) program (since 2016), the Program Coordinator for the Electronic and Information Engineering (EIE) (2015-2022) and the vice-director of the Maker Lab ( since 2019). 

## **Education Background**
- **2006-2008**, Postdoctoral Fellow, *Princeton University*, U.S.A
- **2006**, Doctor of Philosophy, *University of Southern California*, U.S.A
- **1999**, Master of Engineering, *University of Tsukuba*, Japan
- **1996**, Bachelor of Engineering, *The Chinese University of Hong Kong*, Hong Kong

## **Seclected Publications**
- M.O. Pun, M. Morelli and C.-C. Kuo, Multi-Carrier Techniques For Broadband Wireless Communications: A Signal Processing Perspectives, Imperial College Press, U.K. 2007. [[Book Link]](https://books.google.co.uk/books?hl=zh-CN&lr=&id=zl-7CgAAQBAJ&oi=fnd&pg=PR7&dq=Multi-Carrier+Techniques+For+Broadband+Wireless+Communications&ots=E4D4_xRom-&sig=ObnyBEVO-U-k55MAIr3DG2Dqv5A) -->
