```
create_sequence ::= CREATE SEQUENCE [ IF NOT EXISTS ] sequence_name 
                    sequence_options

sequence_name ::= '<Text Literal>'

sequence_options ::= [ INCREMENT [ BY ] increment ] 
                     [ MINVALUE minvalue | NO MINVALUE ] 
                     [ MAXVALUE maxvalue | NO MAXVALUE ] 
                     [ START [ WITH ] start ] [ CACHE cache ]
```