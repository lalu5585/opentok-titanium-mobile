# Opentok

The Opentok object is a top level container for the module itself. It is the result of calling `require(com.tokbox.ti.opentok)` in a project where the module is already referenced in `tiapp.xml`.

<nav>
  <table>
    <tr>
      <th>Methods</th>
      <th>Properties</th>
      <th>Events</th>
    </tr>
    <tr>
      <td>[createSession(_props_)](#createsessionprops)</td>
      <td></td>
      <td></td>
    </tr>
  </table>
</nav>

## Methods

### createSession(_props_)

Create a [Session](session.md#session) object. Only one Session is supported at a time.

Parameters:
*  _props_ (Dictionary):
   *  _sessionId_ (String) _required_ - Session ID. This is generated by a server-side SDK.
   *  _environment_ (String) _optional_ - OpenTok environment to start this Session. Possible values: "staging", "production". Defaults to "staging".

Returns: (Session)