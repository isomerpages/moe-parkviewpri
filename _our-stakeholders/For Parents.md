---
title: For Parents
permalink: /for-parents/
variant: markdown
description: ""
---
<style>
    .container {
        display: grid;
        grid-template-columns: repeat(3, auto);
        gap: 20px;
        justify-content: center;
        margin-top: 10px;
    }

    .container a,
    .container a:hover,
    .container a:focus,
    .container a:active {
        text-decoration: none !important;
    }

    .box {
        width: 200px; 
        height: 200px; 
        padding: 20px;
        border: 0;
        cursor: pointer;
        background: #FADD8F;
        transition: 0.3s;
        font-family: Arial, sans-serif;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .box:hover {
        background: #F8D063;
    }

    .title {
        font-weight: bold;
        font-size: 20px;
        text-align: left;
				color: #051C70;
    }

    .click {
        color: #000000;
        text-decoration: underline;
        text-align: right;
        width: 100%;
    }

    /* Mobile / Handphone view */
    @media screen and (max-width: 768px) {
        .container {
            grid-template-columns: 1fr; /* 1 column */
            gap: 15px;
            margin: 10px;
        }

        .box {
            width: 100%; /* full width of container */
            height: auto; /* adjust height for content */
        }

        .title {
            font-size: 18px;
        }
    }
</style>

<div class="container">
    <a target="_blank" href="https://file.go.gov.sg/pvps-fas.pdf">
        <div class="box">
            <div class="title">Financial Assistance Scheme</div>
            <div class="click">Click here</div>
        </div>
    </a>   
	    <a target="_blank" href="https://parkviewpri.moe.edu.sg/our-stakeholders/insurance-claim/">
        <div class="box">
            <div class="title">Insurance Claim</div>
            <div class="click">Click here</div>
        </div>
	</a> 
    <a target="_blank" href="https://parkviewpri.moe.edu.sg/our-stakeholders/information-for-p1-y2026/">
        <div class="box">
            <div class="title">Information for P1 (Y2026)</div>
            <div class="click">Click here</div>
        </div>
    </a>    
	 <a target="_blank" href="https://parkviewpri.moe.edu.sg/our-stakeholders/letter-to-parents/">
        <div class="box">
            <div class="title">Letter to Parents</div>
            <div class="click">Click here</div>
        </div>
    </a>   
		<a target="_blank" href="https://www.parkviewpri.moe.edu.sg/our-stakeholders/mtp-2026/">
        <div class="box">
            <div class="title">MTP</div>
            <div class="click">Click here</div>
        </div>
    </a>  
		<a target="_blank" href="https://parkviewpri.moe.edu.sg/parents-resources/">
        <div class="box">
            <div class="title">Other Resources</div>
            <div class="click">Click here</div>
        </div>
    </a>  
</div>