===================
``alexapy.aiohttp``
===================

.. automodule:: alexapy.aiohttp

   .. contents::
      :local:


Submodules
==========

.. toctree::

   alexapy.aiohttp.abc
   alexapy.aiohttp.base_protocol
   alexapy.aiohttp.client
   alexapy.aiohttp.client_exceptions
   alexapy.aiohttp.client_proto
   alexapy.aiohttp.client_reqrep
   alexapy.aiohttp.client_ws
   alexapy.aiohttp.connector
   alexapy.aiohttp.cookiejar
   alexapy.aiohttp.formdata
   alexapy.aiohttp.frozenlist
   alexapy.aiohttp.hdrs
   alexapy.aiohttp.helpers
   alexapy.aiohttp.http
   alexapy.aiohttp.http_exceptions
   alexapy.aiohttp.http_parser
   alexapy.aiohttp.http_websocket
   alexapy.aiohttp.http_writer
   alexapy.aiohttp.locks
   alexapy.aiohttp.log
   alexapy.aiohttp.multipart
   alexapy.aiohttp.payload
   alexapy.aiohttp.payload_streamer
   alexapy.aiohttp.pytest_plugin
   alexapy.aiohttp.resolver
   alexapy.aiohttp.signals
   alexapy.aiohttp.streams
   alexapy.aiohttp.tcp_helpers
   alexapy.aiohttp.test_utils
   alexapy.aiohttp.tracing
   alexapy.aiohttp.typedefs
   alexapy.aiohttp.web
   alexapy.aiohttp.web_app
   alexapy.aiohttp.web_exceptions
   alexapy.aiohttp.web_fileresponse
   alexapy.aiohttp.web_log
   alexapy.aiohttp.web_middlewares
   alexapy.aiohttp.web_protocol
   alexapy.aiohttp.web_request
   alexapy.aiohttp.web_response
   alexapy.aiohttp.web_routedef
   alexapy.aiohttp.web_runner
   alexapy.aiohttp.web_server
   alexapy.aiohttp.web_urldispatcher
   alexapy.aiohttp.web_ws

.. currentmodule:: alexapy.aiohttp


Functions
=========

- :py:func:`request`:
  Constructs and sends a request. Returns response object.

- :py:func:`content_disposition_filename`:
  Undocumented.

- :py:func:`parse_content_disposition`:
  Undocumented.

- :py:func:`get_payload`:
  Undocumented.


.. autofunction:: request

.. autofunction:: content_disposition_filename

.. autofunction:: parse_content_disposition

.. autofunction:: get_payload


Classes
=======

- :py:class:`BaseConnector`:
  Base connector class.

- :py:class:`ClientResponse`:
  Undocumented.

- :py:class:`ClientRequest`:
  Undocumented.

- :py:class:`ClientSession`:
  First-class interface for making HTTP requests.

- :py:class:`ClientTimeout`:
  Undocumented.

- :py:class:`ClientWebSocketResponse`:
  Undocumented.

- :py:class:`Fingerprint`:
  Undocumented.

- :py:class:`RequestInfo`:
  Undocumented.

- :py:class:`TCPConnector`:
  TCP connector.

- :py:class:`UnixConnector`:
  Unix socket connector.

- :py:class:`NamedPipeConnector`:
  Named pipe connector.

- :py:class:`CookieJar`:
  Implements cookie storage adhering to RFC 6265.

- :py:class:`DummyCookieJar`:
  Implements a dummy cookie storage.

- :py:class:`FormData`:
  Helper class for multipart/form-data and

- :py:class:`BasicAuth`:
  Http basic authentication helper.

- :py:class:`ChainMapProxy`:
  Abstract base class for generic types.

- :py:class:`HttpVersion`:
  HttpVersion(major, minor)

- :py:class:`WSMsgType`:
  An enumeration.

- :py:class:`WSCloseCode`:
  An enumeration.

- :py:class:`WSMessage`:
  _WSMessageBase(type, data, extra)

- :py:class:`BodyPartReader`:
  Multipart reader for single body part.

- :py:class:`MultipartReader`:
  Multipart body reader.

- :py:class:`MultipartWriter`:
  Multipart body writer.

- :py:class:`AsyncIterablePayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`BufferedReaderPayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`BytesIOPayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`BytesPayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`IOBasePayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`JsonPayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`Payload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`StringIOPayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`StringPayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`TextIOPayload`:
  Helper class that provides a standard way to create an ABC using

- :py:class:`payload_type`:
  Undocumented.

- :py:class:`streamer`:
  Undocumented.

- :py:class:`AsyncResolver`:
  Use the `aiodns` package to make asynchronous DNS lookups

- :py:class:`DefaultResolver`:
  Use Executor for synchronous getaddrinfo() calls, which defaults to

- :py:class:`ThreadedResolver`:
  Use Executor for synchronous getaddrinfo() calls, which defaults to

- :py:class:`Signal`:
  Coroutine-based signal implementation.

- :py:class:`DataQueue`:
  DataQueue is a general-purpose blocking queue with one reader.

- :py:class:`FlowControlDataQueue`:
  FlowControlDataQueue resumes and pauses an underlying stream.

- :py:class:`StreamReader`:
  An enhancement of asyncio.StreamReader.

- :py:class:`TraceConfig`:
  First-class used to trace requests launched via ClientSession

- :py:class:`TraceConnectionCreateEndParams`:
  Parameters sent by the `on_connection_create_end` signal

- :py:class:`TraceConnectionCreateStartParams`:
  Parameters sent by the `on_connection_create_start` signal

- :py:class:`TraceConnectionQueuedEndParams`:
  Parameters sent by the `on_connection_queued_end` signal

- :py:class:`TraceConnectionQueuedStartParams`:
  Parameters sent by the `on_connection_queued_start` signal

- :py:class:`TraceConnectionReuseconnParams`:
  Parameters sent by the `on_connection_reuseconn` signal

- :py:class:`TraceDnsCacheHitParams`:
  Parameters sent by the `on_dns_cache_hit` signal

- :py:class:`TraceDnsCacheMissParams`:
  Parameters sent by the `on_dns_cache_miss` signal

- :py:class:`TraceDnsResolveHostEndParams`:
  Parameters sent by the `on_dns_resolvehost_end` signal

- :py:class:`TraceDnsResolveHostStartParams`:
  Parameters sent by the `on_dns_resolvehost_start` signal

- :py:class:`TraceRequestChunkSentParams`:
  Parameters sent by the `on_request_chunk_sent` signal

- :py:class:`TraceRequestEndParams`:
  Parameters sent by the `on_request_end` signal

- :py:class:`TraceRequestExceptionParams`:
  Parameters sent by the `on_request_exception` signal

- :py:class:`TraceRequestRedirectParams`:
  Parameters sent by the `on_request_redirect` signal

- :py:class:`TraceRequestStartParams`:
  Parameters sent by the `on_request_start` signal

- :py:class:`TraceResponseChunkReceivedParams`:
  Parameters sent by the `on_response_chunk_received` signal


.. autoclass:: BaseConnector
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: BaseConnector
      :parts: 1

.. autoclass:: ClientResponse
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientResponse
      :parts: 1

.. autoclass:: ClientRequest
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientRequest
      :parts: 1

.. autoclass:: ClientSession
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientSession
      :parts: 1

.. autoclass:: ClientTimeout
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientTimeout
      :parts: 1

.. autoclass:: ClientWebSocketResponse
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientWebSocketResponse
      :parts: 1

.. autoclass:: Fingerprint
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: Fingerprint
      :parts: 1

.. autoclass:: RequestInfo
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: RequestInfo
      :parts: 1

.. autoclass:: TCPConnector
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TCPConnector
      :parts: 1

.. autoclass:: UnixConnector
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: UnixConnector
      :parts: 1

.. autoclass:: NamedPipeConnector
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: NamedPipeConnector
      :parts: 1

.. autoclass:: CookieJar
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: CookieJar
      :parts: 1

.. autoclass:: DummyCookieJar
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: DummyCookieJar
      :parts: 1

.. autoclass:: FormData
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: FormData
      :parts: 1

.. autoclass:: BasicAuth
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: BasicAuth
      :parts: 1

.. autoclass:: ChainMapProxy
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: ChainMapProxy
      :parts: 1

.. autoclass:: HttpVersion
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: HttpVersion
      :parts: 1

.. autoclass:: WSMsgType
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: WSMsgType
      :parts: 1

.. autoclass:: WSCloseCode
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: WSCloseCode
      :parts: 1

.. autoclass:: WSMessage
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: WSMessage
      :parts: 1

.. autoclass:: BodyPartReader
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: BodyPartReader
      :parts: 1

.. autoclass:: MultipartReader
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: MultipartReader
      :parts: 1

.. autoclass:: MultipartWriter
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: MultipartWriter
      :parts: 1

.. autoclass:: AsyncIterablePayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: AsyncIterablePayload
      :parts: 1

.. autoclass:: BufferedReaderPayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: BufferedReaderPayload
      :parts: 1

.. autoclass:: BytesIOPayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: BytesIOPayload
      :parts: 1

.. autoclass:: BytesPayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: BytesPayload
      :parts: 1

.. autoclass:: IOBasePayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: IOBasePayload
      :parts: 1

.. autoclass:: JsonPayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: JsonPayload
      :parts: 1

.. autoclass:: Payload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: Payload
      :parts: 1

.. autoclass:: StringIOPayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: StringIOPayload
      :parts: 1

.. autoclass:: StringPayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: StringPayload
      :parts: 1

.. autoclass:: TextIOPayload
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TextIOPayload
      :parts: 1

.. autoclass:: payload_type
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: payload_type
      :parts: 1

.. autoclass:: streamer
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: streamer
      :parts: 1

.. autoclass:: AsyncResolver
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: AsyncResolver
      :parts: 1

.. autoclass:: DefaultResolver
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: DefaultResolver
      :parts: 1

.. autoclass:: ThreadedResolver
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: ThreadedResolver
      :parts: 1

.. autoclass:: Signal
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: Signal
      :parts: 1

.. autoclass:: DataQueue
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: DataQueue
      :parts: 1

.. autoclass:: FlowControlDataQueue
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: FlowControlDataQueue
      :parts: 1

.. autoclass:: StreamReader
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: StreamReader
      :parts: 1

.. autoclass:: TraceConfig
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceConfig
      :parts: 1

.. autoclass:: TraceConnectionCreateEndParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceConnectionCreateEndParams
      :parts: 1

.. autoclass:: TraceConnectionCreateStartParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceConnectionCreateStartParams
      :parts: 1

.. autoclass:: TraceConnectionQueuedEndParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceConnectionQueuedEndParams
      :parts: 1

.. autoclass:: TraceConnectionQueuedStartParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceConnectionQueuedStartParams
      :parts: 1

.. autoclass:: TraceConnectionReuseconnParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceConnectionReuseconnParams
      :parts: 1

.. autoclass:: TraceDnsCacheHitParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceDnsCacheHitParams
      :parts: 1

.. autoclass:: TraceDnsCacheMissParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceDnsCacheMissParams
      :parts: 1

.. autoclass:: TraceDnsResolveHostEndParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceDnsResolveHostEndParams
      :parts: 1

.. autoclass:: TraceDnsResolveHostStartParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceDnsResolveHostStartParams
      :parts: 1

.. autoclass:: TraceRequestChunkSentParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceRequestChunkSentParams
      :parts: 1

.. autoclass:: TraceRequestEndParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceRequestEndParams
      :parts: 1

.. autoclass:: TraceRequestExceptionParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceRequestExceptionParams
      :parts: 1

.. autoclass:: TraceRequestRedirectParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceRequestRedirectParams
      :parts: 1

.. autoclass:: TraceRequestStartParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceRequestStartParams
      :parts: 1

.. autoclass:: TraceResponseChunkReceivedParams
   :members:

   .. rubric:: Inheritance
   .. inheritance-diagram:: TraceResponseChunkReceivedParams
      :parts: 1


Exceptions
==========

- :py:exc:`ClientConnectionError`:
  Base class for client socket errors.

- :py:exc:`ClientConnectorCertificateError`:
  Response certificate error.

- :py:exc:`ClientConnectorError`:
  Client connector error.

- :py:exc:`ClientConnectorSSLError`:
  Response ssl error.

- :py:exc:`ClientError`:
  Base class for client connection errors.

- :py:exc:`ClientHttpProxyError`:
  HTTP proxy error.

- :py:exc:`ClientOSError`:
  OSError error.

- :py:exc:`ClientPayloadError`:
  Response payload error.

- :py:exc:`ClientProxyConnectionError`:
  Proxy connection error.

- :py:exc:`ClientResponseError`:
  Connection error during reading response.

- :py:exc:`ClientSSLError`:
  Base error for ssl.*Errors.

- :py:exc:`ContentTypeError`:
  ContentType found is not valid.

- :py:exc:`InvalidURL`:
  Invalid URL.

- :py:exc:`ServerConnectionError`:
  Server connection errors.

- :py:exc:`ServerDisconnectedError`:
  Server disconnected.

- :py:exc:`ServerFingerprintMismatch`:
  SSL certificate does not match expected fingerprint.

- :py:exc:`ServerTimeoutError`:
  Server timeout error.

- :py:exc:`TooManyRedirects`:
  Client was redirected too many times.

- :py:exc:`WSServerHandshakeError`:
  websocket server handshake error.

- :py:exc:`WebSocketError`:
  WebSocket protocol parser error.

- :py:exc:`BadContentDispositionHeader`:
  Base class for warnings about dubious runtime behavior.

- :py:exc:`BadContentDispositionParam`:
  Base class for warnings about dubious runtime behavior.

- :py:exc:`EofStream`:
  eof stream indication.


.. autoexception:: ClientConnectionError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientConnectionError
      :parts: 1

.. autoexception:: ClientConnectorCertificateError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientConnectorCertificateError
      :parts: 1

.. autoexception:: ClientConnectorError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientConnectorError
      :parts: 1

.. autoexception:: ClientConnectorSSLError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientConnectorSSLError
      :parts: 1

.. autoexception:: ClientError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientError
      :parts: 1

.. autoexception:: ClientHttpProxyError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientHttpProxyError
      :parts: 1

.. autoexception:: ClientOSError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientOSError
      :parts: 1

.. autoexception:: ClientPayloadError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientPayloadError
      :parts: 1

.. autoexception:: ClientProxyConnectionError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientProxyConnectionError
      :parts: 1

.. autoexception:: ClientResponseError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientResponseError
      :parts: 1

.. autoexception:: ClientSSLError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ClientSSLError
      :parts: 1

.. autoexception:: ContentTypeError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ContentTypeError
      :parts: 1

.. autoexception:: InvalidURL

   .. rubric:: Inheritance
   .. inheritance-diagram:: InvalidURL
      :parts: 1

.. autoexception:: ServerConnectionError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ServerConnectionError
      :parts: 1

.. autoexception:: ServerDisconnectedError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ServerDisconnectedError
      :parts: 1

.. autoexception:: ServerFingerprintMismatch

   .. rubric:: Inheritance
   .. inheritance-diagram:: ServerFingerprintMismatch
      :parts: 1

.. autoexception:: ServerTimeoutError

   .. rubric:: Inheritance
   .. inheritance-diagram:: ServerTimeoutError
      :parts: 1

.. autoexception:: TooManyRedirects

   .. rubric:: Inheritance
   .. inheritance-diagram:: TooManyRedirects
      :parts: 1

.. autoexception:: WSServerHandshakeError

   .. rubric:: Inheritance
   .. inheritance-diagram:: WSServerHandshakeError
      :parts: 1

.. autoexception:: WebSocketError

   .. rubric:: Inheritance
   .. inheritance-diagram:: WebSocketError
      :parts: 1

.. autoexception:: BadContentDispositionHeader

   .. rubric:: Inheritance
   .. inheritance-diagram:: BadContentDispositionHeader
      :parts: 1

.. autoexception:: BadContentDispositionParam

   .. rubric:: Inheritance
   .. inheritance-diagram:: BadContentDispositionParam
      :parts: 1

.. autoexception:: EofStream

   .. rubric:: Inheritance
   .. inheritance-diagram:: EofStream
      :parts: 1


Variables
=========

- :py:data:`hdrs`
- :py:data:`HttpVersion10`
- :py:data:`HttpVersion11`
- :py:data:`PAYLOAD_REGISTRY`
- :py:data:`EMPTY_PAYLOAD`

.. autodata:: hdrs
   :annotation:

   .. code-block:: text

      <module 'alexapy.aiohttp.hdrs' from '/Users/alandtse/alexapy/alexapy/aiohttp/hdrs.py'>

.. autodata:: HttpVersion10
   :annotation:

   .. code-block:: text

      HttpVersion(major=1, minor=0)

.. autodata:: HttpVersion11
   :annotation:

   .. code-block:: text

      HttpVersion(major=1, minor=1)

.. autodata:: PAYLOAD_REGISTRY
   :annotation:

   .. code-block:: text

      <alexapy.aiohttp.payload.PayloadRegistry object at 0x112b69590>

.. autodata:: EMPTY_PAYLOAD
   :annotation:

   .. code-block:: text

      <alexapy.aiohttp.streams.EmptyStreamReader object at 0x112b33350>
