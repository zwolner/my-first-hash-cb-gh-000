# My First Hash

## Objectives

1. Practice instantiating hashes
2. Practice adding key/value pairs to hashes
3. Practice retrieving information from hashes

## Instructions 

**Refer back to the previous lesson to help you solve this lab!**

### Challenge I: Instantiating Hashes

* In the `my_hash` method, use the literal constructor to set a variable called `my_hash` equal to a hash with key/value pairs of your choice. 

* Remember, key/values pairs are associative. It doesn't make sense to have a key/value pair of `"my_name" => 78`. It *does* make sense to have a key/value pair of `"my_name" => "Herman Melville"` (if you happen to be that author, of course). 

### Challenge II: Hash with Data

* In the `shipping_manifest` method, set a variable called `shipping_manifest` equal to a hash.
* fill that hash with key/value pairs that describe the following information: 
    * We have 5 whale bone corsets, 2 porcelain vases and 3 oil paintings. Your hash should have the following comma separated key/value pairs:
      * `"whale bone corsets" => 5`
      * `"porcelain vases" => 2`
      * `"oil paintings" => 3`
* **Note:** Build this hash yourself! Don't just copy and paste from the following methods. :)

### Challenge III: Retrieving Data 

* In the `retrieval` method we've given you the shipping_manifest hash that you built out in the previous challenge. Use the `[]` hash method described in the previous readme to return the value of the `"oil paintings"` key of the `shipping_manifest` hash. 
* For example, if we have the following hash: 

```ruby
hash = {"key1" => "value1"}
```

We can return the value of `"key1"` like this: 

```ruby
hash["key1"]
```
### Challenge IV: Adding Data

* In the `adding` method, we've once again given you the shipping_manifest hash. Use the `[]=` method to add the following key/valuve pair to the hash: 
  * `"pearl necklace" => 1`
  * This method *must return the newly-added-to `shipping_hash`*. 
  * Remember that the return value of using the `[]=` method is *the value of the key/value pair you added*. We need our `adding` method to return the `shipping_manifest`. 
  * Here's a refresher on the `[]=` method: 

```ruby 
hash = {"key1" => "value1"}
hash["key2"] = "value2"
# returns "value2"

puts hash
# => {"key1" => "value1", "key2" => "value2"}
```




