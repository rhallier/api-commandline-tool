# Backend Detection

## Get list
POST /controller/restui/backendConfig/getBackendDiscoveryConfigs
{"attachedEntity":{"entityType":"APPLICATION","entityId":{{a:application}}},"agentType":"APP_AGENT"}

[ {
  "id" : 587415,
  "version" : 2,
  "name" : "Default Amazon S3 configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240769,
    "version" : 1,
    "name" : "Bucket Name",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240770,
    "version" : 1,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240771,
    "version" : 1,
    "name" : "Object Key",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : false,
  "supportsCorrelation" : false,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Amazon S3"
}, {
  "id" : 587416,
  "version" : 2,
  "name" : "Default Amazon SNS configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240772,
    "version" : 1,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240773,
    "version" : 1,
    "name" : "Topic ARN",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : false,
  "supportsCorrelation" : false,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Amazon SNS"
}, {
  "id" : 587414,
  "version" : 2,
  "name" : "Default Amazon SQS configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240774,
    "version" : 1,
    "name" : "Destination",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240775,
    "version" : 1,
    "name" : "DestinationType",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Amazon SQS"
}, {
  "id" : 587418,
  "version" : 2,
  "name" : "Default AWS Configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240776,
    "version" : 1,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240777,
    "version" : 1,
    "name" : "Service",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240778,
    "version" : 1,
    "name" : "Endpoint",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : false,
  "supportsCorrelation" : false,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Amazon Web Services"
}, {
  "id" : 587422,
  "version" : 2,
  "name" : "Default Axon configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240779,
    "version" : 1,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240780,
    "version" : 1,
    "name" : "Bus Cluster Name",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240781,
    "version" : 1,
    "name" : "Bus Connector Type",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Axon"
}, {
  "id" : 587411,
  "version" : 2,
  "name" : "Default Cassandra CQL configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240782,
    "version" : 1,
    "name" : "Cluster Name",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240783,
    "version" : 1,
    "name" : "keyspace",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240784,
    "version" : 1,
    "name" : "Host",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240785,
    "version" : 1,
    "name" : "Port",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240786,
    "version" : 1,
    "name" : "Data Center",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240787,
    "version" : 1,
    "name" : "Rack",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Cassandra CQL"
}, {
  "id" : 587405,
  "version" : 2,
  "name" : "Default HTTP configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240788,
    "version" : 1,
    "name" : "Host",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240789,
    "version" : 1,
    "name" : "Port",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240790,
    "version" : 1,
    "name" : "URL",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-segments",
      "value" : "true"
    } ],
    "namingActions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "merge-delimiter",
      "value" : ""
    }, {
      "id" : 0,
      "version" : 0,
      "name" : "segment-count",
      "value" : "2"
    }, {
      "id" : 0,
      "version" : 0,
      "name" : "segment-type",
      "value" : "first-n"
    }, {
      "id" : 0,
      "version" : 0,
      "name" : "split-delimiter",
      "value" : ""
    } ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240791,
    "version" : 1,
    "name" : "Query String",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "HTTP",
  "exitPointSubType" : "HTTP"
}, {
  "id" : 587404,
  "version" : 4,
  "name" : "Default JDBC configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240792,
    "version" : 3,
    "name" : "URL",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240793,
    "version" : 3,
    "name" : "Host",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240794,
    "version" : 3,
    "name" : "Port",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240795,
    "version" : 3,
    "name" : "Database",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240796,
    "version" : 3,
    "name" : "Version",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240797,
    "version" : 3,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : false,
  "supportsCorrelation" : false,
  "priority" : 0,
  "exitPointType" : "JDBC",
  "exitPointSubType" : "JDBC"
}, {
  "id" : 587408,
  "version" : 2,
  "name" : "Default JMS configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240798,
    "version" : 1,
    "name" : "Destination",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240799,
    "version" : 1,
    "name" : "DestinationType",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240800,
    "version" : 1,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "JMS",
  "exitPointSubType" : "JMS"
}, {
  "id" : 587419,
  "version" : 2,
  "name" : "Default Jolt configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240801,
    "version" : 1,
    "name" : "Host",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240802,
    "version" : 1,
    "name" : "Port",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240803,
    "version" : 1,
    "name" : "Service",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Jolt"
}, {
  "id" : 587420,
  "version" : 2,
  "name" : "Default Kafka configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240804,
    "version" : 1,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240805,
    "version" : 1,
    "name" : "Topic Name",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240806,
    "version" : 1,
    "name" : "Broker URL",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Kafka"
}, {
  "id" : 587417,
  "version" : 2,
  "name" : "Default MongoDB configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240807,
    "version" : 1,
    "name" : "Host",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240808,
    "version" : 1,
    "name" : "Port",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240809,
    "version" : 1,
    "name" : "Database",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : false,
  "supportsCorrelation" : false,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Mongo DB"
}, {
  "id" : 587409,
  "version" : 2,
  "name" : "Default MQ configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240810,
    "version" : 1,
    "name" : "Destination",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240811,
    "version" : 1,
    "name" : "DestinationType",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240812,
    "version" : 1,
    "name" : "Host",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240813,
    "version" : 1,
    "name" : "Port",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240814,
    "version" : 1,
    "name" : "Major Version",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240815,
    "version" : 1,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "MQ",
  "exitPointSubType" : "MQ"
}, {
  "id" : 587412,
  "version" : 2,
  "name" : "Default RabbitMQ configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240816,
    "version" : 1,
    "name" : "Host",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240817,
    "version" : 1,
    "name" : "Port",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240818,
    "version" : 1,
    "name" : "Routing Key",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240819,
    "version" : 1,
    "name" : "Exchange",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "RABBITMQ",
  "exitPointSubType" : "RABBITMQ"
}, {
  "id" : 587406,
  "version" : 2,
  "name" : "Default RMI configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240820,
    "version" : 1,
    "name" : "URL",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "RMI",
  "exitPointSubType" : "RMI"
}, {
  "id" : 587410,
  "version" : 2,
  "name" : "Default Thrift configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240821,
    "version" : 1,
    "name" : "Host",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240822,
    "version" : 1,
    "name" : "Port",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240823,
    "version" : 1,
    "name" : "transport",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "THRIFT",
  "exitPointSubType" : "THRIFT"
}, {
  "id" : 587421,
  "version" : 2,
  "name" : "Default Vertx Message configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240824,
    "version" : 1,
    "name" : "Address Type",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240825,
    "version" : 1,
    "name" : "Address",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "CUSTOM",
  "exitPointSubType" : "Vertx-Msg"
}, {
  "id" : 587407,
  "version" : 2,
  "name" : "Default WebService configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240826,
    "version" : 1,
    "name" : "Service",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240827,
    "version" : 1,
    "name" : "URL",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240828,
    "version" : 1,
    "name" : "Operation",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240829,
    "version" : 1,
    "name" : "Soap Action",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  }, {
    "id" : 2240830,
    "version" : 1,
    "name" : "Vendor",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : false,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : true,
  "supportsCorrelation" : true,
  "priority" : 0,
  "exitPointType" : "WEB_SERVICE",
  "exitPointSubType" : "WEB_SERVICE"
}, {
  "id" : 587413,
  "version" : 2,
  "name" : "Default WebSocket configuration",
  "attachedEntity" : {
    "entityType" : "APPLICATION",
    "entityId" : 15719
  },
  "agentType" : "APP_AGENT",
  "discoveryConditions" : [ ],
  "identityOptions" : [ {
    "id" : 2240831,
    "version" : 1,
    "name" : "Endpoint",
    "namingOptions" : [ {
      "id" : 0,
      "version" : 0,
      "name" : "use-entire-string",
      "value" : "true"
    } ],
    "namingActions" : [ ],
    "enabled" : true,
    "segmentType" : null,
    "segmentCount" : null,
    "customSegment" : null,
    "segmentMergeDelimiter" : null,
    "splitDelimiter" : null,
    "regexMergeDelimiter" : null,
    "regex" : null,
    "regexGroups" : null
  } ],
  "discoveryEnabled" : true,
  "correlationEnabled" : false,
  "supportsCorrelation" : false,
  "priority" : 0,
  "exitPointType" : "WEBSOCKET",
  "exitPointSubType" : "WEBSOCKET"
} ]

--------------------------------------------------------------------------------------------------------------

## Update
POST /controller/restui/backendConfig/updateBackendDiscoveryConfig

{
  "id": 587422,
  "version": 2,
  "name": "Default Axon configuration",
  "attachedEntity": {
    "entityType": "APPLICATION",
    "entityId": 15719
  },
  "agentType": "APP_AGENT",
  "discoveryConditions": [],
  "identityOptions": [
    {
      "id": 2240779,
      "version": 1,
      "name": "Vendor",
      "namingOptions": [
        {
          "id": 0,
          "version": 0,
          "name": "use-entire-string",
          "value": "true"
        }
      ],
      "namingActions": [],
      "enabled": true,
      "segmentType": "first-n",
      "segmentCount": "",
      "customSegment": "",
      "segmentMergeDelimiter": "",
      "splitDelimiter": "",
      "regexMergeDelimiter": "",
      "regex": "",
      "regexGroups": ""
    },
    {
      "id": 2240780,
      "version": 1,
      "name": "Bus Cluster Name",
      "namingOptions": [
        {
          "id": 0,
          "version": 0,
          "name": "use-entire-string",
          "value": "true"
        }
      ],
      "namingActions": [],
      "enabled": true,
      "segmentType": "first-n",
      "segmentCount": "",
      "customSegment": "",
      "segmentMergeDelimiter": "",
      "splitDelimiter": "",
      "regexMergeDelimiter": "",
      "regex": "",
      "regexGroups": ""
    },
    {
      "id": 2240781,
      "version": 1,
      "name": "Bus Connector Type",
      "namingOptions": [
        {
          "id": 0,
          "version": 0,
          "name": "use-entire-string",
          "value": "true"
        }
      ],
      "namingActions": [],
      "enabled": false,
      "segmentType": "first-n",
      "segmentCount": "",
      "customSegment": "",
      "segmentMergeDelimiter": "",
      "splitDelimiter": "",
      "regexMergeDelimiter": "",
      "regex": "",
      "regexGroups": ""
    }
  ],
  "discoveryEnabled": true,
  "correlationEnabled": true,
  "supportsCorrelation": true,
  "priority": 0,
  "exitPointType": "CUSTOM",
  "exitPointSubType": "Axon"
}