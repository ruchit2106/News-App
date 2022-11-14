# News App

## About:

A mobile application responsible for current articles daily with filter options.

## Packages:

<ul>
<li>cached_network_image: ^3.2.1</li>
<li>cupertino_icons: ^1.0.5</li>
<li>flutter:sdk: flutter</li>
<li>google_fonts: ^3.0.1</li>
<li>http: ^0.13.4</li>
<li>lint: ^1.8.2</li>
<li>webview_flutter: ^3.0.4</li>
</ul>

## Description:

<ul>
<li> CRUD Operations of the app was performed by building an SQFLite database. </li>
<li> Clean Architecture was implements by dividing the app into sub-components:
<ul>

<li> model <ul>
<li> category_model </li>
<li> note_model </li>
</ul>
</li>

<li> screens <ul>
<li>Aboutus</li>
<li> edit_note_screen </li>
<li> notes_detail_screen </li>
<li> notes_screen </li>
<li> splash_screen </li>
</ul>
</li>

<li> sqflite_database <ul>
<li> db </li>
</ul>
</li>

<li> widgets <ul>
<li>main</li>
</ul>
</li>

</ul> 
</li></li>
</ul>
Comments in the code, helps for better understanding of how the app works.

## Features:

<ul>
<li>Add a new Note</li>
<li>Update Note</li>
<li>Delete Note</li>
<li>Share a Note</li>
<li>View All Notes</li>
</ul>

### To Run the App:

In the command terminal, run the following commands:

    $ flutter pub get
    $ flutter run
