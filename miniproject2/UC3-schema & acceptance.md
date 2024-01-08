<table>
    <tr>
        <td><font size=5><b>Use Case UC-3:&nbsp;&nbsp;&nbsp;Alert</b></font>
        </td>
	</tr>
	<tr>
        <td>
            <font size=4>
                <b>
                    Related Requierment's:
                </b>
            </font>
            <br>
            REQ3
            <br>
            <font size=4>
                <b>
                    Initiating Actor:
                </b>
            </font>
            <br>
            User
            <br>
            <font size=4>
                <b>
                    Actor’s Goal:
                </b>
            </font>
            <br>
            Choose alert music from the standard library or the local music file.
            <br>
            <font size=4>
                <b>
                    Participating Actors:
                </b>
            </font>
            <br>
            Database, Local files
            <br>
            <font size=4>
                <b>
                    Preconditions:
                </b>
            </font>
            <br>
            The alert music that the user want to choose must be exist in the standard library or the local file.
            <br>
            <font size=4>
                <b>
                    Postconditions:
                </b>
            </font>
            <br>
            The app alert music has changed to the chosen music.
            <br>
            <font size=4>
                <b>
                    Flow of Events for Main Success Scenario:
            <br>
            <br>
                    →&nbsp;&nbsp;&nbsp;&nbsp;
                </b>
            </font>
            1.&nbsp;&nbsp; User choose the 'Setting' item and touch the 'Change alert music' button.
            <br>
            <font size=4>
                <b>
            ←&nbsp;&nbsp;&nbsp;&nbsp;
                </b>
            </font>
            2.&nbsp;&nbsp; System
            <br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)gets the music list of the standard library from the Database.
            <br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b)shows user the music list and give user an extra option 'Find music from local files'.
            <br>
            <font size=4>
                <b>
            →&nbsp;&nbsp;&nbsp;&nbsp;
                </b>
            </font>
            3.&nbsp;&nbsp; User choose music from list or choose an local audio file.
            <br>
            <font size=4>
                <b>
            ←&nbsp;&nbsp;&nbsp;&nbsp;
                </b>
            </font>
            4.&nbsp;&nbsp; System
            <br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)Read the current audio file from local files,and change alert music.
            <br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b)signals to the user 'change successful'. 
        </td>
    </tr>
</table>






<table>
    <tr>
        <td colspan=2>
            <font size=4>
                <b>
                    Test-case Identifier:
                </b>
            </font>
            <br>
            TC-3
            <br>
            <font size=4>
                <b>
                Use Case Tested:
                </b>
            </font>
            <br>
            UC-3
            <br>
            <font size=4>
                <b>
                Pass/fail Criteria:
                </b>
            </font>
            <br>
            The test passes if the user choose the music that is already exist in the standard library or is a local audio file.
            <br>
            <font size=4>
                <b>
            Input Data:
                </b>
            </font>
            <br>
            nothing.
            <br>
        </td>
	</tr>
    <font size=4>
        <b>
            <tr>
                <td width=550>
                    Test Procedure:
                </td>
                <td>
                    Expected Result:
                </td>
            </tr>
        </b>
    </font>
    <tr>
    	<td>
            Step 1:Choose 
            a local audio file.
            <br>
            <br>
            <br>
            Step 2:Choose a local file but not an audio file.
        </td>
        <td>
            System return the message that 'change successful' and change the alert music.
            <br>
            <br>
            System return the message that 'file type error'
        </td>
    </tr>
</table>












































































