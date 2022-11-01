### This is a Header


![image](https://user-images.githubusercontent.com/117183230/199265821-f3ce012d-fbd3-4089-866c-8c4a439efbe5.png)


using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class CameraController : MonoBehaviour
{
    public GameObject player;
    private Vector3 offset;
    // Start is called before the first frame update
    void Start()
    {
        offset = transform.position - player.transform.position;
    }

    // Update is called once per frame
    void LateUpdate()
    {
        transform.position = player.transform.position + offset;
    }
}


- [ ] wake up
- [ ] do job
- [ ] make money
