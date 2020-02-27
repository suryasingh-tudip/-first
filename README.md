<div class="section" id="ch">
<devsite-heading text="Ch" for="ch_1" level="h2" link="" toc="" back-to-top=""><h2 is-upgraded="" id="ch_1">Ch<a href="#top_of_page" class="devsite-back-to-top-link material-icons" data-title="Back to top"></a></h2></devsite-heading>
<p>The "acl ch" (or "acl change") command updates access control lists, similar
in spirit to the Linux chmod command. You can specify multiple access grant
additions and deletions in a single command run; all changes will be made
atomically to each object in turn. For example, if the command requests
deleting one grant and adding a different grant, the ACLs being updated will
never be left in an intermediate state where one grant has been deleted but
the second grant not yet added. Each change specifies a user or group grant
to add or delete, and for grant additions, one of R, W, O (for the
permission to be granted). A more formal description is provided in a later
section; below we provide examples.</p>
</div>
