# Regex
This is smart way to comment two xml tags


https://regex101.com/r/pC6Kox/1


Ldap Modify Commands :

./ldapmodify -h hostname -p 10389 -D "cn=User"  -w "Password" -f file.ldif

Patter in file.ldif
dn: entryUUID=getfromdirectorystudio
changetype: modify
add: LastLoggedInTimes
LastLoggedInTimes:




--------------------------------------------------------------------------------
Regex - <button[^>]*>((?!<\/button>)[\s\S])*?<span>[\s\S]*?<\/button>


Content -
-------------

<button class="b1"
    (click)="b1()">
    <mat-icon>icon</mat-icon>
</button>

<button class="b1"
    (click)="b1()">
    <mat-icon>othericon</mat-icon>
    <span>Some Text</span>
</button>


