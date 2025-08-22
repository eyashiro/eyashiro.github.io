---
#layout: page
layout: page-fullwidth
title: "Editing and Proofreading (Scientific + General)"
subheadline: "Life Sciences Research Support"
#teaser: ""
permalink: "/posts/editing-rates-and-currency-calculator"
header:
    image: "services-editing.jpg"
    background-color: ""
---


<style>
#container{
  background-color:#ABEBC6;
  padding:5px;
  text-align:left;
  border-radius:15px;
  }

        .calculator {
            max-width: 400px;
            margin: 0 auto;
            padding: 1em;
            border: 1px solid #ccc;
            border-radius: 1em;
        }
        .calculator h2 {
            text-align: center;
        }
        .result {
            margin-top: 1em;
            text-align: center;
            font-weight: bold;
        }
        button {
          margin:auto;
          display:block;
          }

.button0 {
  border: non;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 15px;
}

.button1 {background-color: #04AA6D;} /* Green */
.button2 {background-color: #008CBA;} /* Blue */

.buttons-inline {
  display: flex;
  gap: 12px;            /* controls spacing */
  justify-content: center;
  flex-wrap: wrap;
  }


.emoji-marker {
  list-style: none;          /* reset to control marker */
  padding-left: 0.5rem;      /* control gutter width */
}
.emoji-marker li { list-style-position: outside; }

/* Per-variant marker content */
.emoji-marker li.ok::marker   { content: "✅  "; color: #16a34a; }
.emoji-marker li.no::marker   { content: "❌  "; color: #dc2626; }
.emoji-marker li.lightbulb::marker { content: "💡  "; color: #f59e0b; }
.emoji-marker li.pointright::marker { content: "👉  "; color: #f59e0b; }
.emoji-marker li.portfolio::marker { content: "🎓  "; color: #f59e0b; }

/* Optional: keep marker aligned with text size */
.emoji-marker li::marker { font-size: 1em; }
</style>

<br />

Grammar mistakes and convoluted sentences kill your readers’ attention. Formatting inconsistencies are also eye-sores that grind on your readers' patience. Many people even believe that poorly-written documents are simply not very professional. What all this means is that you need to care about your stakeholders! They're your readers after all!

Audiences also tend to enjoy a piece of writing when every sentence makes sense and sends clear messages. Clear messages mean clear results and greater reach among your audiences.

#### Action plan
<ul class="emoji-marker">
  <li class="pointright">Request editing and proofreading service by <a href="../contact/index.html">clicking here.</a></li>
  <li class="pointright">Get awkward sentences smoothed out, clarity improved, and ensure your writing meets stakeholder expectations and publication standards.</li>
  <li class="pointright">Overcome language barriers and communicate your messages effectively with expert editing and proofreading.</li>
</ul>


## What's included
<br />
<div class="row" id="container">
  <div class="medium-4 column">
    <h4 style="text-align: center;">Language accuracy</h4>
    <p><ul>
    <li>Fix grammar and punctuation. </li>
    <li>Align formality level. </li>
    <li>Improve word choice</li>
    <li>Fix awkward sentences. </li>
    <li>Improve narrative flow.</li></ul></p>
  </div>
  <div class="medium-4 column">
    <h4 style="text-align:center;">Style and Formatting</h4>
    <p><ul>
    <li>Apply the right style guides and document conventions. </li></ul>
    e.g., Style guide preferences, Journal/agency house style, American vs. British English spelling</p>
  </div>
  <div class="medium-4 column">
    <h4 style="text-align:center;">Ensure Consistency</h4>
    <p><ul>
    <li>Standardize terminology, tone, and presentation throughout.</li>
    <li>Ensure a smooth reading experience for your target audiences.</li></ul>
    </p>
  </div>
</div>

## Types of documents
**Technical documents:** STEM and Clinical Sciences
* Reports
* Manuscripts
* White papers
* Grant proposals
* Doctoral and Master's theses
* Conference abstracts
* Cover letters
* Applications (scholarships, fellowships, study programs)
* Presentations / Slide decks
* Protocols
* and more.

**Other document types:** General Topics
* Emails
* Webpages
* College application essays
* and more.

## Levels of editing

  * **Standard Editing:** Check for linguistic mistakes, formatting, style, consistency, and flow within sentences.
  * **Substantive Editing:** *Standard Editing* plus improve word usage, sentence structure, and flow throughout the manuscript. Detect missing and misplaced information. Point out any scientific issues I encounter.

Unless requested, the reference section of scientific documents is not checked because people normally use reference managers to format references automatically.


## Pricing

|   Editing level  |     Price*     |
|------------------|:-------------:|
| Standard editing | 0.06 eur/word |
| Substantive editing | 0.09 eur/word |
| Editing top-up of documents requiring <br />a substantial amount of corrections\*\* | +0.02 eur/word |

\* The price excludes VAT. Businesses within Germany will be charged a 19% VAT. Businesses within the EU will be reverse charge. Businesses outside of the EU will be responsible for their own VAT. Individuals not affiliated with a business will be charged the German 19% VAT.

\*\* The word rate will be determined upon inspection of the document's writing quality. The top-up is to account for the extra time I will need to correct a very poorly written document. It is my experience that most documents are polished enough when handed to me that the top-up is not required.

<br />
## Learn more about my past projects, jobs, and clients:
* <a href="../../portfolio/editing/index.html">Client testimonials and certifications.</a>


<br />

<div class="mar">
  <div class="row align-center">
      <div class="buttons-inline">
        <a class="button0 button2" href="../../contact/index.html">Start A Project</a>
        <a class="button0 button2" href="../../services/">Explore Other Services</a>
      </div>
  </div>
</div>

<br /><br />

<a name="Price-Calculator"></a>

<script>
    function calculatePrice() {
        const wordCount = document.getElementById('wordCount').value;
        const options = document.getElementsByName('option');
        let pricePerWord = 0;
        for (const option of options) {
            if (option.checked) {
                pricePerWord = parseFloat(option.value);
                break;
            }
        }
        const totalPrice = wordCount * pricePerWord;
        document.getElementById('result').textContent = `Total Price: €${totalPrice.toFixed(2)}`;
    }
</script>
<div class="calculator">
    <h2>Document Price Calculator</h2>
    <br />
    <div>Select editing level:</div>
    <br />
    <div>
            <input type="radio" name="option" value="0.06" checked />
            <span> &nbsp; Standard: &nbsp; 0.06 eur/word</span> <br />
            <input type="radio" name="option" value="0.09" />
            <span>&nbsp; Substantive: &nbsp; 0.09 eur/word</span> <br />
            <input type="radio" name="option" value="0.08" />
            <span>&nbsp; Standard + top-up: &nbsp; 0.08 eur/word</span> <br />
            <input type="radio" name="option" value="0.11" />
            <span>&nbsp; Substantive + top-up: &nbsp; 0.11 eur/word</span> <br />
    </div>
   <br />
   <label for="wordCount">Number of Words in your document:</label>
   <input type="number" id="wordCount" placeholder="Enter number of words">
   <div>
   <button onclick="calculatePrice()">Calculate Price</button></div>

   <div class="result" id="result"></div>
</div>

<br />
<br />

<a name="Currency-Converter"></a>

<div style="text-align:center">
<script src="https://cdn.logwork.com/widget/currency_converter.js"></script>
<a href="https://logwork.com/free-currency-converter-calculator" class="currency_convertor" data-currencies="EUR,USD,CAD,JPY,GBP,CHF,CNY,INR">Currency Converter</a>
</div>

<br /><br />

<div class="mar">
  <div class="row align-center">
      <div class="buttons-inline">
        <a class="button0 button2" href="../../contact/index.html">Start A Project</a>
        <a class="button0 button2" href="../../services/">Explore Other Services</a>
      </div>
  </div>
</div>
<p style="text-align:right;"><a href="#Top">Back to top</a></p>
