# Monash Bootcamp Challenge 1

## Project Description

Optimise provided codebase so that it follows accessibility standards.

## Acceptance Criteria

Given a webpage meets accessibility standards

1. WHEN I view the source code THEN I find semantic HTML elements
2. WHEN I view the structure of the HTML elements THEN I find that the elements follow a logical structure independent of styling and positioning
3. WHEN I view the image elements THEN I find accessible alt attributes
4. WHEN I view the heading attributes THEN they fall in sequential order
5. WHEN I view the title element THEN I find a concise, descriptive title

## Deployment

My website is available [here](https://yipchisan.github.io/monash-bootcamp-challenge-1/).

## Screenshot

How my website looks like

![Screenshot](./docs/assets/images/screenshot.png)

## Modifications

| Which Acceptance Criteria is based on |                                                                                              Modification                                                                                               |
| :-----------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                   1                   |                                               Change the `div` with `class="header"` to `header` element and also change the corresponding css selectors                                                |
|                   1                   |                                                                      Change the `div` with `class="content"` to `section` element                                                                       |
|                   1                   |                                                             Change the `div` with `class="search-engine-optimization"` to `article` element                                                             |
|                   1                   |                                                            Change the `div` with `class="online-reputation-management"` to `article` element                                                            |
|                   1                   |                                                               Change the `div` with `class="social-media-marketing"` to `article` element                                                               |
|                   1                   |                                                                       Change the `div` with `class="benefits"` to `aside` element                                                                       |
|                   1                   |                                                                    Change the `div` with `class="benefit-lead"` to `article` element                                                                    |
|                   1                   |                                                                   Change the `div` with `class="benefit-brand"` to `article` element                                                                    |
|                   1                   |                                                                    Change the `div` with `class="benefit-cost"` to `article` element                                                                    |
|                   1                   |                                               Change the `div` with `class="footer"` to `footer` element and also change the corresponding css selectors                                                |
|                   2                   | Combine `class="search-engine-optimization"`, `class="online-reputation-management"` and `class="social-media-marketing"` to one single class `service` and also change the corresponding css selectors |
|                   2                   |                  Combine `class="benefit-lead"`, `class="benefit-brand"` and `class="benefit-cost"` to one single class `benefit-item` and also change the corresponding css selectors                  |
|                   3                   |                                                                                     Add `alt` to each `img` element                                                                                     |
|                   4                   |                                                                         Change the `h2` element inside `footer` element to `h3`                                                                         |
|                   5                   |                                                                            Change the `title` value to _Horiseon Home Page_                                                                             |
