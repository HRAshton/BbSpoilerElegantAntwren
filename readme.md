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
elegantantwren
eaheader
easubheader
ealeftsubheader
earightsubheader
ealeft
earight
```

5. Save changes.

## Usage

For create the spoiler use **[elegantantwren]** tag. It must contain next tags in the right order:
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
