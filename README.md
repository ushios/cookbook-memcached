cookbook-memcached
==================

Install memcached

# Install

## Case: submodule

    $ git submodule add ${this_url} cookbooks/memcached


# Usage

## Sample in roles

    name "memcached"
    description "memcached"
    run_list(
	    "recipe[memcached]"
	)