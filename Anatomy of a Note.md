---
title: Anatomy of a Note
tags: 
author: @BrentRitchie
source: 
---
# Anatomy of a Note

Typically I see a note broken down into several parts. Not all of these are present all the time, but these are the general types that you will see.

## Front Matter

The [[Front Matter]] is probably the most contentious part for note takers. Many people are split on whether it's useful and many applications treat it differently. If the front matter was defined and treated consistently then I could see value in using it. But it's a bit of a free-for-all right now and needs to be further defined.

## Title

Some people like to use the current date and time as a title, but I find it a bit too obtuse. I like to use a title that is easy to use in a sentence for easy wiki-style links.

There is also debate on where it should be stored. Some of the more popular options are the filename, the top level title,  or a property called title in the front matter.

## Table of Contents

This section can be controversial because there are two (2) trains of thought. One side says that each note should be small and not need a table of contents. Others say that a nate should be allowed to grow over time and sometimes may need a table of contents to keep everything accessible.

I personally don't prefer one argument over another. Some of my notes can be extremely small and consist of a single paragraph. Some notes though can be extremely large because it may describe different aspects of a single thing. Most of my notes documenting server configurations are like this.

## Overview

The overview section of a note is generally the first section and is usually the most consistent part. This section uses simple prose to describe the concept in very broad terms. Generally inline links are used to link out to more specific and supporting concepts. This is the type of note that most Zettelkasten gurus describe as a "good" note. It will often be the prose section directly under the top-level heading.

## Information Dump

Some people like to add technical and procedural information for specific notes like recipes, software specs, and data analysis, to name a few. If sections like this had a more definite structure, it would be easier to navigate and find links in the [[Knowledge Graph]].

These sections make heavy use of tables, lists, and graphs. Incorporating some of this metadata would be ideal, especially since [[Hyper Text Markup Language]]'s primary goal is to describe data structure.

## To-Do's

I believe that listing To-Do's in a dedicated document is the easiest way to manage them. Especially when you are doing several projects at once. Putting the To-Do's directly alongside other notes or even inside of them, take a lot of effort to manage if special tooling isn't used. And I really want to find a method that is as tooling independent as possible.

Currently I use a plugin called vscode-todo-md, and it is great but has some shortcomings. These are all a design decision and based on the fact that the author wants to keep it extremely simple and one line per task. However I want to track a set of to-dos that have dependencies, start dates and several other complications. This is not congruent with a simple task-per-line model. It is also contradictory with my minimal tooling requirement.