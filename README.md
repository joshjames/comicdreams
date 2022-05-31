# comicdreams
openAI - dall-e - comic books brought to life

## What is this ?

The future project for ComicDreams - a proof of concept openAI project using Dall-e and marvel comics as a source to transform static comic books
as well as their text in to vivid animations.  
Every Comic book fans dream.  

Project is work in progress at the moment.

## Stage 1.
Content source - scanning/capturing downloading comics.
running through datalibrary input for data source, with the idea to capture the entire marvel library in to openAI's source content.
scanning and dumping existing marvel cartoons frame by frame as source content using meta content to accompany the comic frames for learning
output examples.

## stage 2.
OCR to metadata, capture and isolate every comic frame and OCR the text accompaying every frame stored as an xml object.
currently using ContentName.pg#.frame#.img with accomponying ContentName.pg#.frame#.xml
XML source will be broken down in to
<naratter> text describing the scene and story </narrater>
<character>words by character </character>
<character2>words by character 2  </character2>
Intents and the verb/description by narrater will be added as tags at the base of the metadata
<tags>#intent,#action,#verb  i.e #spacescene #action #shooting </tags>
### cartoon - output image frames.
VLC shell took > capture input mp4 > output image frames. to seperate use character recognition (tensor flow)

## Stage 3.
proof. running dalle, comparison against computer vision projects and other machine learning methods.
run 1000 frames against 5 contendors and dalle.
publish results.

## stage 4
fine tune and improve.

## stage 5
custom.
the end goal is a watchable animated story made up from nothing but the input of a comicbook.
watchable, story driven animations that make sense completly created by A.I
the future of entertainment.
Robots really do dream of... well anything :)

