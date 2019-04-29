# DMT3Notes
## Unity
Find Obj by Tag
```cs
GameObject.FindGameObjectsWithTag("tag");
```
## Modify Object
### Rotate
```cs
obj.transform.Rotate(0,0,2.0F);
```
### Set Active
```cs
obj.SetActive(! obj.activeSelf);
```
## Key Inputs
```cs
if (Input.GetKeyDown("space"))
```
## Mouse Events
```cs
void OnMouseDown()
```
## Arduino
Analoge Ports am Arduino nur für Inputs!

```cs
SceneManager.LoadScene(activeSceneIndex);
 // oder
SceneManager.LoadScene("MyScene");
```
