1. Check `vm.swappiness` on all your nodes<br>
    <code>[root@cm-inst1 ~]# cat /proc/sys/vm/swappiness</code><br>
    <code>1</code>
    
2. Show the mount attributes of all volumes<br>

3. Show the reserve space of any non-root, `ext`-based volumes
    * XFS volumes do not use reserve space
4. Disable transparent hugepages
4. List your network interface configuration
5. List forward and reverse host lookups using `getent` or `nslookup`
6. Show the <code>nscd</code> service is running
7. Show the <code>ntpd</code> service is running<br>
