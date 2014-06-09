node-amfutils
=============

Node.JS module that provides an API for encoding and decoding of AMF0 and AMF3 protocols

This little module provides few tools helping encoding and decoding of AMF0/3 using Node's buffers.

Usage
==

    var amfUtils = require('node-amfutils');
    
    var buffer = amfUtils.amf0Encode([{ a: "xxx"},b: null]);
    
    

Here is a short list of the utils it provide:

decodeAmf3Cmd
====

Decodes AMF3 encoded command

encodeAmf3Cmd
====

Encodes AMF3 encoded command

decodeAmf0Cmd
====

Decodes AMF3 encoded command

encodeAmf0Cmd
====

Encodes AMF3 encoded command


amf0Encode / amf3Encode
====

Encode Javascript object in AMF0/3

amf0EncodeOne / amf3EncodeOne
====

Encode one JavaScript variable in AMF0/3

amf0Decode / amf3Decode
====

Decode AMF0/3 into JavaScript object

amf0DecodeOne / amf3DecodeOne
====

Decode one only amf0/3 command into JavaScript

Other tools
====

amf0cnvA2O
amf0cnvO2A
amf0markSArray
amf0decArray
amf0decBool
amf0decDate
amf0decLongString
amf0decNull
amf0decNumber
amf0decObject
amf0decRef
amf0decSArray
amf0decString
amf0decTypedObj
amf0decUndefined
amf0decXmlDoc
amf0encArray
amf0encBool
amf0encDate
amf0encLongString
amf0encNull
amf0encNumber
amf0encObject
amf0encRef
amf0encSArray
amf0encString
amf0encTypedObj
amf0encUndefined
amf0encXmlDoc
amf3decArray
amf3decByteArray
amf3decDate
amf3decDouble
amf3decFalse
amf3decInteger
amf3decNull
amf3decObject
amf3decString
amf3decTrue
amf3decUI29
amf3decUndefined
amf3decXml
amf3decXmlDoc
amf3encArray
amf3encByteArray
amf3encDate
amf3encDouble
amf3encFalse
amf3encInteger
amf3encNull
amf3encObject
amf3encString
amf3encTrue
amf3encUI29
amf3encUndefined
amf3encXml
amf3encXmlDoc
