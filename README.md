
[source](https://github.com/kuandeng/LightGCN/tree/master/Data/amazon-book)

* `train.txt`
  * Train file.
  * Each line is a user with her/his positive interactions with items: userID\t a list of itemID\n.

* `test.txt`
  * Test file (positive instances).
  * Each line is a user with her/his positive interactions with items: userID\t a list of itemID\n.
  * Note that here we treat all unobserved interactions as the negative instances when reporting performance.
  
* `user_list.txt`
  * User file.
  * Each line is a triplet (org_id, remap_id) for one user, where org_id and remap_id represent the ID of the user in the original and our datasets, respectively.
  
* `item_list.txt`
  * Item file.
  * Each line is a triplet (org_id, remap_id) for one item, where org_id and remap_id represent the ID of the item in the original and our datasets, respectively.

```
.
├── [1.5M]  item_list.txt
├── [3.7M]  test.txt
├── [ 13M]  train.txt       
└── [1.0M]  user_list.txt

  20M used in 0 directories, 4 files
```