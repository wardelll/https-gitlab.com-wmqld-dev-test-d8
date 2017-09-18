# Wesley Mission QLD Drupal 8 test

You don't have to complete the whole test.
Complete as much as you think necessary to demonstrate your skills.

## Section 1: documentation

1. Update current README.md file. 
2. Add THEME section and list your preferred Drupal theme (or themes). 
3. List pros, cons and possible usage of the theme (or themes).
4. Provide solution as `feature/section-1-doc` branch.

## Section 2: configuration

1. Create content type `Petition`.
2. Add fields:
    * `Category` taxonomy reference to `Petition Category` vocabulary
    * `Closing date` date and time [compulsory] 
3. Display `Category` and `Closing date` as inline label and field value.
4. Export above content type, fields and taxonomy as Feature
    * add feature files and folders to root folder of this repository 
    * provide solution as `feature/section-2-config` branch.

## Section 3: contributed modules

1. Add URL pattern for `Petition` content type: `petition/[title]`.
2. Display `Category` and `Closing date` in separate columns one next to another.
3. Create view to display
    * page with all petitions 
    * block with 5 latest petitions 
4. Update feature from `Section 2` 
    * add feature files and folders to root folder of this repository 
    * provide solution as `feature/section-3-modules` branch.

## Section 4: development

1. Add administrator form to above module to set `Default petition life span` in days.
2. Add `Start date` date and time field to `Petition` content type.
3. Change `Closing date` field value automatically based on `Start date` and `Default petition life span`.
4. Update feature from Sections 2 and 3.  
    * add feature files and folders to root folder of this repository 
    * add other necessary files to complete above task
    * provide solution as `feature/section-4-devel` branch.

## Section 5: git

1. Merge all 4 above branches into 1.
2. Provide solution as `feature/section-X-merge` branch.

## Section 6: theme

1. Prefered theme.
    * Zen
2. Pros
    * Basic and responsive, great to use as a foundation.
3. Cons
    * Built using HTML 5 so it may not be suitable for projects requiring legacy browser support. 
