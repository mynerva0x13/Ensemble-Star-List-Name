# Ensemble Stars Character List and Assigned Unit inside of Agency

## Overview

This JSON file provides a structured list of agencies from the **Ensemble Stars** universe, including the units (groups) within each agency and the members of those units. It is designed for a small project use case, simplifying the organization and retrieval of character information based on their assigned unit and agency.

## JSON Structure

The JSON file consists of an array of agency objects. Each agency object contains:
- **AgencyID**: A unique identifier for the agency.
- **name**: The name of the agency.
- **units**: An array of unit objects belonging to the agency.

Each unit object contains:
- **unitID**: A unique identifier for the unit.
- **unitName**: The name of the unit group.
- **members**: An array of member objects in the unit.

Each member object contains:
- **memberID**: A unique identifier for the character.
- **name**: The name of the character.

## Example JSON Structure

```json
[
  {
    "AgencyID": 0,
    "name": "STARMAKER PRODUCTION",
    "units": [
      {
        "unitID": 0,
        "unitName": "Fines",
        "members": [
          { "memberID": 1, "name": "Eichi Tenshouin" },
          { "memberID": 2, "name": "Wataru Hibiki" }
        ]
      }
    ]
  }
]
```

## List of Agencies and Units

1. **STARMAKER PRODUCTION**
   - Units:
     - **Fines**: Eichi Tenshouin, Wataru Hibiki, Tori Himemiya, Yuzuru Fushimi
     - **Trickstar**: Hokuto Hidaka, Subaru Akehoshi, Makoto Yuuki, Mao Isara
     - **Ryusentai**: Chiaki Morisawa, Kanata Shinkai, Tetora Nagumo, Midori Takamine, Shinobu Sengoku
     - **Alkaloids**: Hiiro Amagi, Aira Shiratori, Mayoi Ayase, Tatsumi Kazehaya

2. **COSMIC PRODUCTION**
   - Units:
     - **Eden**: Nagisa Ran, Hiyori Tomoe, Ibara Saegusa, Jun Sazanami
     - **Valkyrie**: Shu Itsuki, Mika Kagehira
     - **2winks**: Hinata Aoi, Yuta Aoi
     - **Crazy:B**: Rinne Amagi, HiMERU, Kohaku Oukawa, Niki Shiina

3. **Rhythm Link**
   - Units:
     - **Undead**: Rei Sakuma, Kaoru Hakaze, Koga Oogami, Adonis Otogari
     - **Ra*bits**: Tomoya Mashiro, Nazuna Nito, Mitsuru Tenma, Hajime Shino
     - **Akatsuki**: Keito Hasumi, Kuro Kiryu, Souma Kanzaki

4. **NEW DIMENSION**
   - Units:
     - **Knights**: Tsukasa Suou, Leo Tsukinaga, Izumi Sena, Ritsu Sakuma, Arashi Narukami
     - **Switch**: Natsume Sakasaki, Tsumugi Aoba, Sora Harukawa
     - **MaM**: Madara Mikejima

5. **THUNDERBOLT CHALLENGE**
   - Members: Esu Sagiri, Ibuki Taki, Kanna Natsu, Fuyume Hanamura, Raika Hojo, Nice Arneb Thunder

6. **Other Characters**
   - Members: Jin Sagami, Akiomi Kunugi, Seiya Hidaka, Anzu

## Usage

This file is useful for:
- Displaying character information categorized by agency and unit.
- Organizing character data for a project or application involving **Ensemble Stars**.
- Easily accessing the unit members based on their agency affiliation.

## Notes

- This list does not cover all characters from the **Ensemble Stars** series, only a subset relevant for a specific small project.
- The `AgencyID`, `unitID`, and `memberID` fields are used as identifiers and may not match any official numbering from the series.

## Contribution

Feel free to expand the list with more characters or units as needed for your project!
