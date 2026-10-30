# Data Centric Programming Assignment 2026
## Gaming session tracker
- [Assignment Brief](dataset_assignment.md)

# Questions
1. Which game do I play most?
2. Which game gives me the best average mood?
3. Does my mood change when I win more matches than I lose?

# Data Dictionary
| Column | Type | Unit | How I measure it |
|--------|------|------|------------------|
| date | date | YYYY-MM-DD | Day of the session |
| game | category | text | Name of the game |
| hours | decimal | hours | Session length, taken from my game clock or start and end times |
| mode | category | solo or coop | Whether I played alone or with others |
| wins | integer | count | Matches I won in the session, tallied by me as I play |
| losses | integer | count | Matches I lost in the session, tallied by me as I play |
| mood_1_to_5 | integer | 1 to 5 | How I felt after the session, 1 is low and 5 is high |

# Description of the project
I will record my gaming sessions by hand. After each session I note the game, how long I played, whether I played solo or co-op, the wins, the losses and my mood. My data is in gamingtracker/my_data.csv. I add one row per session and commit it every day.

# Instructions for use

# How it works:

# Findings

# List of files in the project

| Files | Source |
|-----------|-----------|
| main.py | Self written |
| test.py | Modified from [reference]() |
| test.py | From [reference]() |

# References
* Item 1
* Item 2

# What I am most proud of in the assignment

Bla bla bla

# What I learned

Bla bla bla

## Below is how to use Markdown. You can delete this:

## This is how to markdown text:

This is *emphasis*

This is a bulleted list

- Item
- Item

This is a numbered list

1. Item
1. Item

This is a [hyperlink](http://bryanduggan.org)

# Headings
## Headings
#### Headings
##### Headings

This is code:

```Java
public void render()
{
	ui.noFill();
	ui.stroke(255);
	ui.rect(x, y, width, height);
	ui.textAlign(PApplet.CENTER, PApplet.CENTER);
	ui.text(text, x + width * 0.5f, y + height * 0.5f);
}
```

So is this without specifying the language:

```
public void render()
{
	ui.noFill();
	ui.stroke(255);
	ui.rect(x, y, width, height);
	ui.textAlign(PApplet.CENTER, PApplet.CENTER);
	ui.text(text, x + width * 0.5f, y + height * 0.5f);
}
```

This is an image using a relative URL:

![An image](images/p8.png)

This is an image using an absolute URL:

![A different image](https://bryanduggandotorg.files.wordpress.com/2019/02/infinite-forms-00045.png?w=595&h=&zoom=2)

This is a youtube video:

[![YouTube](http://img.youtube.com/vi/J2kHSSFA4NU/0.jpg)](https://www.youtube.com/watch?v=J2kHSSFA4NU)

This is a table:

| Heading 1 | Heading 2 |
|-----------|-----------|
|Some stuff | Some more stuff in this column |
|Some stuff | Some more stuff in this column |
|Some stuff | Some more stuff in this column |

|Some stuff | Some more stuff in this column |
