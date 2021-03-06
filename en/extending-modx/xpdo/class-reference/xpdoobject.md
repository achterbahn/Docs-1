---
title: "xPDOObject"
_old_id: "1287"
_old_uri: "2.x/class-reference/xpdoobject"
---

Most of the magic of xPDO is packed into the class xPDOObject. This class is the base persistence class which every domain class and table class you create with xPDO will derive it's properties and behavior from. xPDOObject is a domain class and an Active Record pattern implementation, where each instance represents a row in a specific database table.

1. [Static Object Loaders](extending-modx/xpdo/class-reference/xpdoobject/static-object-loaders)
  1. [\_loadRows](extending-modx/xpdo/class-reference/xpdoobject/static-object-loaders/loadrows)
  2. [\_loadInstance](extending-modx/xpdo/class-reference/xpdoobject/static-object-loaders/loadinstance)
  3. [\_loadCollectionInstance](extending-modx/xpdo/class-reference/xpdoobject/static-object-loaders/loadcollectioninstance)
  4. [load](extending-modx/xpdo/class-reference/xpdoobject/static-object-loaders/load)
  5. [loadCollection](extending-modx/xpdo/class-reference/xpdoobject/static-object-loaders/loadcollection)
  6. [loadCollectionGraph](extending-modx/xpdo/class-reference/xpdoobject/static-object-loaders/loadcollectiongraph)
  7. [Using Custom Loader Classes](extending-modx/xpdo/class-reference/xpdoobject/static-object-loaders/using-custom-loader-classes)
2. [Configuration Accessors](extending-modx/xpdo/class-reference/xpdoobject/configuration-accessors)
  1. [getOption](extending-modx/xpdo/class-reference/xpdoobject/configuration-accessors/getoption)
  2. [setOption](extending-modx/xpdo/class-reference/xpdoobject/configuration-accessors/setoption)
3. [Field Accessors](extending-modx/xpdo/class-reference/xpdoobject/field-accessors)
  1. [get](extending-modx/xpdo/class-reference/xpdoobject/field-accessors/get)
  2. [set](extending-modx/xpdo/class-reference/xpdoobject/field-accessors/set)
  3. [toArray](extending-modx/xpdo/class-reference/xpdoobject/field-accessors/toarray)
  4. [fromArray](extending-modx/xpdo/class-reference/xpdoobject/field-accessors/fromarray)
  5. [toJSON](extending-modx/xpdo/class-reference/xpdoobject/field-accessors/tojson)
  6. [fromJSON](extending-modx/xpdo/class-reference/xpdoobject/field-accessors/fromjson)
4. [Related Object Accessors](extending-modx/xpdo/class-reference/xpdoobject/related-object-accessors)
  1. [getOne](extending-modx/xpdo/class-reference/xpdoobject/related-object-accessors/getone)
  2. [getMany](extending-modx/xpdo/class-reference/xpdoobject/related-object-accessors/getmany)
  3. [addOne](extending-modx/xpdo/class-reference/xpdoobject/related-object-accessors/addone)
  4. [addMany](extending-modx/xpdo/class-reference/xpdoobject/related-object-accessors/addmany)
5. [Persistence Methods](extending-modx/xpdo/class-reference/xpdoobject/persistence-methods)
  1. [save](extending-modx/xpdo/class-reference/xpdoobject/persistence-methods/save)
  2. [remove](extending-modx/xpdo/class-reference/xpdoobject/persistence-methods/remove)
6. [Metadata Accessors](extending-modx/xpdo/class-reference/xpdoobject/metadata-accessors)
  1. [getSelectColumns](extending-modx/xpdo/class-reference/xpdoobject/metadata-accessors/getselectcolumns)
  2. [getPK](extending-modx/xpdo/class-reference/xpdoobject/metadata-accessors/getpk)
  3. [getPKType](extending-modx/xpdo/class-reference/xpdoobject/metadata-accessors/getpktype)
  4. [getFKClass](extending-modx/xpdo/class-reference/xpdoobject/metadata-accessors/getfkclass)
  5. [getFKDefinition](extending-modx/xpdo/class-reference/xpdoobject/metadata-accessors/getfkdefinition)
  6. [getFieldName](extending-modx/xpdo/class-reference/xpdoobject/metadata-accessors/getfieldname)
7. [Validation](extending-modx/xpdo/class-reference/xpdoobject/validation)
  1. [addValidationRule](extending-modx/xpdo/class-reference/xpdoobject/validation/addvalidationrule)
  2. [removeValidationRules](extending-modx/xpdo/class-reference/xpdoobject/validation/removevalidationrules)
  3. [getValidator](extending-modx/xpdo/class-reference/xpdoobject/validation/getvalidator)
  4. [validate](extending-modx/xpdo/class-reference/xpdoobject/validation/validate)
  5. [isValidated](extending-modx/xpdo/class-reference/xpdoobject/validation/isvalidated)
8. [State Accessors](extending-modx/xpdo/class-reference/xpdoobject/state-accessors)
  1. [isLazy](extending-modx/xpdo/class-reference/xpdoobject/state-accessors/islazy)
  2. [isDirty](extending-modx/xpdo/class-reference/xpdoobject/state-accessors/isdirty)
  3. [isNew](extending-modx/xpdo/class-reference/xpdoobject/state-accessors/isnew)