using UnityEngine;
using UnityEngine.SceneManagement;
using UnityEngine.UI; //(ENG)If you do not need to show the name of the scene when loading, then this can be deleted. (RU) Если при загрузке не нужно показывать название сцены, то это можно удалить.

public class SceneTransfer : MonoBehaviour
{
    public Text _sceneNameText; //(ENG)If you do not need to show the name of the scene when loading, then this can be deleted. (RU) Если при загрузке не нужно показывать название сцены, то это можно удалить.

    private void Start()
    {
        _sceneNameText.text = SceneManager.GetActiveScene().name; //(ENG)If you do not need to show the name of the scene when loading, then this can be deleted. (RU) Если при загрузке не нужно показывать название сцены, то это можно удалить.
    }

    public void ChangeScene(string sceneName)
    {
        SceneManager.LoadScene(sceneName);
    }
}
