# Microsoft-Visual-Basic-6.0
Private Sub Login_Load(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles MyBase.Load

        Me.KeyPreview = True

End Sub

 

Private Sub Login_KeyDown(ByVal sender As Object, ByVal e As System.Windows.Forms.KeyEventArgs) Handles Me.KeyDown

        Select Case e.KeyCode

            Case Keys.Up

                Me.PictureBox1.Location = New Point(Me.PictureBox1.Location.X, Me.PictureBox1.Location.Y - 10)

            Case Keys.Down

                Me.PictureBox1.Location = New Point(Me.PictureBox1.Location.X, Me.PictureBox1.Location.Y + 10)

            Case Keys.Left

                Me.PictureBox1.Location = New Point(Me.PictureBox1.Location.X - 10, Me.PictureBox1.Location.Y)

            Case Keys.Right

                Me.PictureBox1.Location = New Point(Me.PictureBox1.Location.X + 10, Me.PictureBox1.Location.Y)

        End Select

End Sub
