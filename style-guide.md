# Style Guide

### SAM

![](https://r12a.github.io/c/Syriac/070F.png)

The SYRIAC ABBREVIATION is a line drawn horizontally above one or more characters, which may or may not have diacritics. 

#### Location

At the end of a word or group of characters that is followed by a character other than a Syriac letter or diacritic mark. Ideally, the SYRIAC ABBREVIATION has a dot at each end and the center, as seen in the examples shown in this proposal. However, while not preferable, it has become acceptable for computers to render the SYRIAC ABBREVIATION as a line without the dots. The line is acceptable for the presentation of Syriac in plain text, while the presence of dots is recommended in liturgical texts.  

#### Uses 

There are two general uses: **letter numbers, and contractions** (Robinson 1962). 

The SYRIAC ABBREVIATION is generally placed extending from above the final character of the word toward the front until the first tall character is reached. A common exception to this rule is found with letter numbers that are preceded by a preposition character as seen in the second line below.

![](https://r12a.github.io/scripts/syriac/images/sam_numeric.png)

Reference: https://www.unicode.org/L2/L1998/98050-syriac-proposal.pdf


***


### Currency

I believe it behooves us to follow the [CLDR Arabic Number Formatting Patterns](https://st.unicode.org/cldr-apps/v#/ar/Number_Formatting_Patterns/)

**Symbol**: XDR U+00A4 ¤

The currency sign ¤ is a character used to denote an unspecified currency.


***


### Date/time format

I believe it best for us to follow the [CLDR Arabic Number Formatting Patterns](https://st.unicode.org/cldr-apps/v#/ar/Number_Formatting_Patterns/) 

1. **Date**
   1. Standard
      - Full: EEEE، d MMMM y
 
        ܚܕܒܫܒܐ، 5 ܐܝܠܘܠ 1999

      - Long: d MMMM y

        5 ܐܝܠܘܠ 1999 

      - Medium: dd‏/MM‏/y

        5 ܐܝܠܘܠ 1999

      - Short: d‏/M‏/y

        1999-09-05

   2. Day Period

      - AM: ܩܛ ܩ (ܒܬܪ ܛܗܪܐ) 
      - PM: ܒܛ ܒ (ܩܕ݇ܡ ܛܗܪܢ)

2. **Time**

      - Full: h:mm:ss a zzzz

        1:25:59 ܒܛ Eastern Standard Time

      - Long: h:mm:ss a z

        1:25:59 ܒܛ EST

      - Medium: h:mm:ss a

        1:25:59 ܒܛ

      - Short: h:mm a

        1:25 ܒܛ

***


### Numbering

We should follow the latin numbering system but should NOT follow the Arabic-Indic digit patterns.

1. Numbers
   1. Standard 

      - standard-decimal: #,##0.###

      - standard-currency: ¤ #,##0.00

      - standard-percent: #,##0%

      - standard-scientific: #E0

      - accounting-currency: ¤#,##0.00;(¤#,##0.00)

   2. Currency Patterns

      - One: {0} {1}, e.g. 1.00 USD, 1 USD

      - Other: {0} {1}, e.g. 1.23 USD, 0.00 USD

   3. Patterns

      - approximately: ~{0}      
      - atLeast: ≥{0}
      - atMost: ≤{0}
      - range: {0}–{1}

   4. Cardinal Numbers

      - Hundred:  ܡܐܐ ܡܵܐܐ 
      - Thousand: ܐܠܦܐ ܐܲܠܦܵܐ
      - Ten thousand: ܪܒܘܬܐ ܪܸܒܘܼܬܵܐ
      - Million: ܡܠܝܘܢ ܡܸܠܝܘܿܢ
      - Billion: ܒܠܝܘܢ ܒܸܠܝܘܿܢ
      - Trillion: ܬܪܠܝܘܢ ܬܪܹܠܝܘܿܢ
      - Quadrillion: ܡܠܝܪܕ ܡܸܠܝܵܪܕ
