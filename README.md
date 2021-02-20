# Vincent Van Gogh Gallery Data Preprocessor

This is a project to train a Machine Learning model based in the Vinvent Van
Gogh collection data. In here the script takes the scraped data feom the
Webpage, and creates an alternative representation with the JSON data.

The data is divided in different tables taking into account different aspects of
the gallery (i.e.: description, related work, search tags, image, among others).
the missing data is completed with default values and then with each new
alternative table (alternative representation for the ML model) the script
integrate them into an star model with. This creates a unique data registerfor
the future stages to process.

Originaly developed for the final project for the tittle of Digital humanities
Msc. degree between 2019 - 2021.

The code was refactored and commented for the official and final presentation
for the 2020/2021 project of the Uniandes Digital Humanities graduate program.

---

## **Project Structure**

**LICENSE:** MIT Project license description.

**README:** Project general description.

**PROJECT STRUCTURE:**

* _**\*\Abstraction**_ #TODO.

  * _**StarDataStruct-VVG-Large:**_ #TODO.
  * _**VStarDataStruct-VVG-Large:**_ #TODO.

* _**\*\Data**_ is the folder containing the CSV files containing the gallery's
  scraped data.
  * _**\*Source:**_ #TODO
    * _**VanGoghGallery_large.csv**_ Gallery's large file with 964 register of Vincent Van
      Gogh work.
    * _**VanGoghGallery_small.csv**_ Gallery's small file with 61 register of Vincent Van
      Gogh work. Useful for functional tests.
  * _**\*Star:**_ #TODO
    * _**\*Small:**_ #TODO
    * _**\*Large:**_ #TODO

---

## Data Structure

First, description of the CSV files inside the _**\*\Data\Source**_ folder goes as follows:

* _ID:_ element ID in the gallery and local folder name.
* _TITLE:_ tittle of the element in the gallery.
* _COLLECTION\_URL:_ recovered element (paint) URL.
* _DOWNLOAD\_URL:_ direct image URL/link for the image in the gallery.
* _HAS\_PICTURE:_ boolean if there is a picture file in the local folder.
* _DESCRIPTION:_ JSON with the description of the element.
* _SEARCH\_TAGS:_ JSON with the collection tags of the element.
* _OBJ\_DATA:_ JSON with the museum object data of the element.
* _RELATED\_WORKS:_ JSON with the related work text and URLs of the element.
* _IMG\_DATA:_ numpy RGB matrix created from original image.

Second, description of the CSV files inside the _**\*\Data\Source**_ folder goes as follows:

* _**\*data-object-alt.csv:**_ #TODO
* _**\*description-alt.csv:**_ #TODO
* _**\*related-work-alt.csv:**_ #TODO
* _**\*search-tags-alt.csv:**_ #TODO
* _**\*img-data:**_ #TODO
* _**\*VVG-Star-Gallery-Collection.csv:**_ #TODO

---

## Important Notes

* _KMINE:_ # TODO [KMINE](https://www.knime.com/)

---
