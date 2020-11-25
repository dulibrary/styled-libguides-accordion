# styled-libguides-accordion
Instructions to make a styled accordion out of libguides boxes.

## Example
We will recreate the accordion displayed at [Accordion Sample: Tutors](https://davenport.libguides.com/accordion).

## Create your boxes (which will become accordion panels)
1. From the LibGuides Admin page, select `Add box`
2. Title your box
3. Select `Floating Box`
4. Click `Save`

## Add HTML to your boxes
1. Within your box, click `Add / Reorder`
2. Select `Rich Text / HTML`
3. Select the `Source` option (so you can edit the HTML directly)
4. Paste in the [new-accordion-panel](https://github.com/brianholda/styled-libguides-accordion/blob/main/new-accordion-panel) code
5. In the code:
  1. Change `#panel-name` to a unique ID name for this particular panel (e.g. `#panel-name` becomes `#technology-tutors`).
  2. Change `Panel Name` to a similar unique title (e.g. `Panel Name` becomes `Technology Tutors`).
  3. Change `id="panel-name"` to match the unique ID name you chose in step 1 (in our example, it'd be `id="technology-tutors"`).
  4. Replace `<!-- [accordion panel body content] -->` with your own code to fill in the accordion panel body (see below for an example)
6. Click `Save & Close`

## Fill in the accordion panel body content
This can be filled however you wish. Here I will give a sample we use for our tutoring accordion.
1. Replace `<!-- [accordion panel body content] -->` with pasted content found 

