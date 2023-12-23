# UE5 Starsiege:Tribes - Mapping

## Start

### Prerequisites 

- Unreal Engine `5.3.2`
- Visual Studios `2022`
  -  You will need the following Visual Studios packages, you can install via your `Visual Studio Installer` application. 

2.) Take the `ModFPSZ.zip` file and export the entire contents to your `.../YourProject/Plugins`

### Import Heightmaps into Unreal Engine 5

##### To begin; Download Unreal Engine 5.

1.) Go to your content directory folder within the editor.
![doc/img.png](doc/img.png)
2.) Create Folder structure by right-clicking, and selecting `New Folder`

![doc/img_1.png](doc/img_1.png) 

name it `Heightmaps` and open it up.

![doc/img_2.png](doc/img_2.png)

3.) Import your heightmap

![doc/img_3.png](doc/img_3.png)

You should see something as such

![doc/img_4.png](doc/img_4.png)

4.) Now right click on the open area and navigate to the bottom go to `Miscellaneous > Data Asset` 

![doc/img_5.png](doc/img_5.png)

You will be given a filter menu, you will need to search for `Terrain Asset`.

![doc/img_7.png](doc/img_7.png)

4.) Create a name such a `TA_Broadside`, and now open it.

Depending on the map that you imported, and working on will determine the height and scale that you set your map to.

Please reference the tables below. If this is a custom made heightmap disregard the tables below.

![doc/img_6.png](doc/img_6.png)





## Maps & Game Modes v1.0.8

If the map shows an `x` within the Available column, then that terrain asset is available to be used natively.

#### Basic Maps

| Available | Map                     | Terrain Asset        | Height | Scale | Game Mode  | Heightmap |
|:----------|:------------------------|:---------------------|:-------|:------|:-----------|:----------|
| x         | Welcome                 | TA_Welcome           | 232    | 8     | Training   | x         |
| x         | Weapons                 | TA_Weapons           | 284    | 8     | Training   | x         |
| x         | Vehicle                 | TA_Vehicle           | 70     | 8     | Training   | x         |
| x         | Commander TargetLaser   | TA_Commander         | 232    | 8     | Training   | x         |
| x         | CTF                     | TA_CTF               | 100    | 8     | Training   | x         |
| x         | Towers                  | TA_Towers            | 170    | 8     | Training   | x         |
| x         | Retrieval               | TA_Retrieval         | 148    | 8     | Training   | x         |
| x         | Destroy                 | TA_Destroy           | 148    | 8     | Training   | x         |

#### Defend & Destroy

| Available | Map                     | Terrain Asset        | Height | Scale | Game Mode        | Heightmap |
|:----------|:------------------------|:---------------------|:-------|:------|:-----------------|:----------|
|           | A Dish Best Served Cold |                      | 233    |       | Defend & Destroy | x         |
|           | BloodyVengeance         |                      | 105    |       | Defend & Destroy | x         |
|           | Hammer Down             |                      | 261    |       | Defend & Destroy | x         |
|           | No Quarter              |                      | 86     |       | Defend & Destroy | x         |
|           | Seek And Destroy        |                      | 159    |       | Defend & Destroy | x         |
|           | Siege                   |                      | 250    |       | Defend & Destroy | x         |


#### Find & Retrieve 

| Available | Map                     | Terrain Asset        | Height | Scale | Game Mode        | Heightmap |
|:----------|:------------------------|:---------------------|:-------|:------|:-----------------|:----------|
|           | DeathKnell              |                      | 138    |       | Find & Retrieve  | x         |
|           | Fallen                  |                      | 100    |       | Find & Retrieve  | x         |
|           | Fog of War              |                      | 119    |       | Find & Retrieve  | x         |
|           | Mudslide                |                      | 240    |       | Find & Retrieve  | x         |
|           | No Man's Land           |                      | 158    |       | Find & Retrieve  | x         |
|           | Strung Out              |                      | 305    |       | Find & Retrieve  | x         |


#### Capture & Hold

| Available | Map                     | Terrain Asset        | Height | Scale | Game Mode        | Heightmap |
|:----------|:------------------------|:---------------------|:-------|:------|:-----------------|:----------|
|           | Ant Hill                |                      | 153    |       | Capture & Hold   | x         |
|           | Citadels                |                      | 94     |       | Capture & Hold   | x         |
|           | Criss Cross             |                      | 152    |       | Capture & Hold   | x         |
|           | Peak Performance        |                      | 167    |       | Capture & Hold   | x         |
|           | Temple Of Doom          |                      | 73     |       | Capture & Hold   | x         |

#### Death Match

| Available | Map                     | Terrain Asset        | Height | Scale | Game Mode        | Heightmap |
|:----------|:------------------------|:---------------------|:-------|:------|:-----------------|:----------|
|           | Blood Runs Cold         |                      | 35     |       | Death Match      | x         |
|           | King Under The Hill     |                      | 291    |       | Death Match      | x         |
|           | Peekaboo                |                      | 284    |       | Death Match      | x         |
|           | Sand Storm              |                      | 64     |       | Death Match      | x         |
|           | The Red Sands           |                      | 115    |       | Death Match      | x         |


#### Mission Training

| Available | Map                     | Terrain Asset        | Height | Scale | Game Mode        | Heightmap |
|:----------|:------------------------|:---------------------|:-------|:------|:-----------------|:----------|
|           | Four Way Dance          |                      | 102    |       | Mission Training | x         |
|           | Free For All            |                      | 153    |       | Mission Training | x         |
|           | Lucky Seven             |                      | 62     |       | Mission Training | x         |
|           | Triple Threat           |                      | 230    |       | Mission Training | x         |


#### Capture The Flag

| Available | Map                     | Terrain Asset        | Height | Scale | Game Mode        | Heightmap |
|:----------|:------------------------|:---------------------|:-------|:------|:-----------------|:----------|
| x         | Blastside               | TA_Broadside         | -      | -     | Capture The Flag | x         |
| x         | Desert Of Death         | TA_DesertOfDeath     | 107    | 8     | Capture The Flag | x         |
| x         | Ice Ridge               | TA_IceRidge          | 144    | 8     | Capture The Flag | x         |
| x         | Broadside               | TA_Broadside         | 232    | 8     | Capture The Flag | x         |
| x         | Dangerous Crossing      | TA_DangerousCrossing | 284    | 8     | Capture The Flag | x         |
| x         | Raindance               | TA_Raindance         | 70     | 8     | Capture The Flag | x         |
| x         | RollerCoaster           | TA_RollerCoaster     | 232    | 8     | Capture The Flag | x         |
| x         | Snowblind               | TA_Snowblind         | 100    | 8     | Capture The Flag | x         |
| x         | Stonehenge              | TA_Stonehenge        | 170    | 8     | Capture The Flag | x         |
| x         | Valhalla                | TA_Valhalla          | 148    | 8     | Capture The Flag | x         |


## Maps & Game Modes v1.1.1

## Community Maps
