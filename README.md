# MissionNaming
Generate random mission codenames

## Instalation

    pip install mission_naming


## Usage

### From python
    
    >>> import mission_naming
    >>> mission_naming.generate() # Generate a random name
    'EMPTY CHAMPION'
    >>> mission_naming.generate(2) # Generate a name given an index
    'BLUE MARKSMAN'
    >>> mission_naming.generate(2) # Same name is returned for same index
    'BLUE MARKSMAN'
    >>> mission_naming.generate(2, seed=3256) # Generate a name given an index different random seed
    'LEAD STARDUST'
    >>> mission_naming.generate(2, seed=3) # Same name is returned for same index and same random seed
    'LEAD STARDUST'
    >>> mission_naming.generate(10000) # only 4028 random unique names can be generated, if index is > 4028 a mission number is suffixed
    'FROZEN SUNDANCE III'
    
    

### Using command_line tool
    
    $ mission_name 
    BEIGE STARBURST
