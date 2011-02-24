Mongo: Memory Handling
-------------

###Memory Mapped
* virtual memory <div class="subtext">(OS virtual memory manager, LRU)</div>
* cache index and data
* one cache <div class="subtext">not OS cache and database cache</div>
* collection tends to be stick together
* auto grow => Memory Hungry