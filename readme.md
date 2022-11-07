# Styles for customized BB spoiler

Example:
![Screenshot](assets/Screenshot.png)

## Compiling

You may use any sass-to-css tool to create .css file. For example, [https://codebeautify.org/sass-to-css-converter].

## Setting up

1. Open the Administrative panel of a forum.

2. Upload the .css file on the "Files" tab and copy the link.

3. Open the "Forms" tab and add following line to "HTML top" section:
```
<link rel="stylesheet" href="LINK_TO_CSS" />
```
Where __LINK_TO_CSS__ is the link copied on the previous step.

4. Add following link to "User`s bb-tags" section:
```
elegantantwren[div.elegant-antwren]
eaheader[div.ea-header]
easubheader[div.ea-subheader]
ealeftsubheader[div.ea-left-subheader]
earightsubheader[div.ea-right-subheader]
ealeft[div.ea-left]
earight[div.ea-right]
```

5. Save changes.

## Usage

There are 2 variants of using the style.

### With bb-codes (if you have administrator rights)

To create the spoiler use **[elegantantwren]** tag. It must contain next tags in the right order:
1. eaheader
1. easubheader
1. ealeftsubheader
1. earightsubheader
1. ealeft
1. earight

Example for the screenshot:

```
[elegantantwren]
[eaheader]Kitty[/eaheader]
[easubheader]Warm | Soft | Blue | 100% kawaii[/easubheader]
[ealeftsubheader]Description[/ealeftsubheader]
[earightsubheader]Information[/earightsubheader]
[ealeft]
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
[/ealeft]
[earight]
The right window
[/earight]
[/elegantantwren]

[elegantantwren]
[eaheader]Turkey[/eaheader]
[easubheader]Cold | Hard | White | 100% taste[/easubheader]
[ealeftsubheader]Description[/ealeftsubheader]
[earightsubheader]Information[/earightsubheader]
[ealeft]
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
[/ealeft]
[earight]
The right window
[/earight]
[/elegantantwren]
```

### With html (if you haven't administrator rights)

To create the spoiler add style file and use ```<div class="elegant-antwren"``` tag. It must contain div tags with next classes in the right order:
1. ea-header
1. ea-subheader
1. ea-left-subheader
1. ea-right-subheader
1. ea-left
1. ea-right

You can use this link for compiled styles: [http://forumstatic.ru/files/001b/c1/44/79971.css]

Example for the screenshot:

```
[html]
<link rel="stylesheet" type="text/css" href="//forumstatic.ru/files/001b/c1/44/79971.css" />

<div class="elegant-antwren">

<div class="ea-header">Kitty</div>
<div class="ea-subheader">Warm | Soft | Blue | 100% kawaii</div>

<div class="ea-left-subheader">Description</div>
<div class="ea-right-subheader">Actions</div>

<div class="ea-left">
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
</div>
<div class="ea-right">
The right window
</div>

</div>
<div class="elegant-antwren">

<div class="ea-header">Kitty</div>
<div class="ea-subheader">Warm | Soft | Blue | 100% kawaii</div>

<div class="ea-left-subheader">Description</div>
<div class="ea-right-subheader">Actions</div>

<div class="ea-left">
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
</div>
<div class="ea-right">
The right window
</div>

</div>
[/html]
```
