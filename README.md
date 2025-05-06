# cs384-project-2--gui-based-transcript-generator-solved
**TO GET THIS SOLUTION VISIT:** [CS384 Project 2- GUI Based Transcript Generator Solved](https://www.ankitcodinghub.com/product/cs384-project-2-gui-based-transcript-generator-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96465&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS384 Project 2- GUI Based Transcript Generator Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Project 2 CS384 – GUI Based Transcript Generator

You need to make the transcript for IIT Antartica after generating their results. IIT Antartica since its far away, they were inspired from IIT Logo and replicated it. Refer the tut05 that you have already done, in which you computed SPI CPI. Now the job is to make the SPI CPI output into a PDF for transcript (Check sample transcript: 0402CS99.pdf in transcriptsIITP folder. That needs to be replicated exactly). You can make a gui interface or a web interface. As always use python for processing data but for pdf too you need to use a Python supported pdf generation library (pypdf..etc., there are many).

Options that needs to be provided.

1. This interface will have option to enter a range of roll numbers. Then on single click the program should generate all the transcript for that range. So if range is 0401cs10-0401cs15, it will generate 6 pdfs. In case the range is 0401cs10- 0401cs80 (and roll number for 0401cs60-0401cs80 dont exists, just dont generate the files for 0401cs60-0401cs80, but do generate the transcript whose roll numbers exists. Also, pop a list saying that these roll numbers dont exists.). A valid range 0401cs60-0401cs60, in this case only one transcript is generated 0401cs60. Save all file names in upper case. When provided a range, do case-insensitive matching. So 0401cs10-0401cs15, 0401cs10-0401CS15, 0401CS10-0401cs15, 0401CS10-0401CS15 generates the same output.

Generate all the transcripts in the folder: transcriptsIITP

2. Option 2 is to generate all transcripts. Here given the grades.csv file, first extract all the unique roll numbers and generate all the transcripts in the folder: transcriptsIITP

Filename will be ROLL NUMBER.pdf in UPPER CASE. If for a student only info till sem4 is available then transcript will be till sem4 only. Page size rule is same, btech a3, others a4.

Page Size:

Since BTech is 8 semesters so what happens here you can not fit all the marks on A4 paper so you need to make the PDF size to A3. However for MTech MSc and PhD the semester usually two or four so you can easily fit on A4 sheet so from the roll number check bit 3 and bit 4. That will provide you this information regarding btech, mtech, phd. 01-btech, 11-mtech, 12-msc, 21 phd. if Bit3/bit4 is 01 its btech (so a3 page) and if anything else then assume it to be masters/phd (so A4 page).

Instead of Date of Issue line keep a line for Date Generated, and generate a system date dd-MM-yyyy hh:mm, e.g., 28 Oct 2021, 19:05

Date Generated: 28 Oct 2021, 19:05. Since this time is system generated, so it will have some offset when computing large number of transcript. So first transcript may have Date Generated: 28 Oct 2021, 19:05 and the last one may have Date Generated: 28 Oct 2021, 19:12 depending how many are being generated.

For signature and seal, there should be space provided. In the GUI, keep an option to upload SEAL and signature. Both shall be optional, if not provided, then it will be blank however, the text for signature (Assitant Registrar (Academic)) shall be there irrespctive if sign is there or not.

Helpful links https://towardsdatascience.com/creating-pdf-files-with-python-ad3ccadfae0f https://stackoverflow.com/questions/2252726/how-to-create-pdf-files-in-python

Check sample transcript: 0402CS99.pdf in transcriptsIITP folder.

IITP logo and hindi text is your responsibility to search and add. 1

</div>
</div>
</div>
