---
layout: post
title:  "HT G3 diary"
# crawlertitle: "How to use jekyll"
summary: "Day 1"
date:   2018-11-30 23:09:47 +0700
categories: Project
tags: 'HT Project'
author: Bo Yang
---
Discuss the protocol of RNA-seq for the DE analysis in scilife.
  Main point:
    1. Know the background of data (only platform, size and type, do not know the source, maybe this is secret).
      Platform NextSeq 500 System, NextSeq 500/550 High Output v2 kit (75-bp read length, single end, dual index)
      Type: 	 FASTQ
      Size: 	 15GB [(4 samples + 1 control) *3]
    2. Decide the protocol for the analysis.
      There are two ways for the analysis in order to discuss in seminar tomorrow before making final decision.
      Common steps: 
        a. Adapter removal(cutadapt) 
        b. Quality Control(FASTQC/HTQC) 
        c. Quality filter(sickle)
      Branches:
        first version:
          d. ncDNA removal(bowtie) 
          e. genome alignment(bowtie)
          f. normalisation
          g. DeEseq2
         second version:
          d. kallisto
          e. DEseq2
     3. Create this diary for recording future work!
     4. Main problems for the future.
        a. The script writing for the pepline.
        b. Allocation in the group.
        c. Schedule plan for the project.

#{% highlight ruby %}
#def print_hi(name)
#  puts "Hi, #{name}"
#end
#print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
#{% endhighlight %}

