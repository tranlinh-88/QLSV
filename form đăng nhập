# Form đăng nhập
Public Class frmDangnhap
    Private Sub bntDangnhap_Click(sender As Object, e As EventArgs) Handles bntDangnhap.Click
        If txtTaikhoan.Text = "admin" And txtMatkhau.Text = "admin" Then
            MessageBox.Show("Đăng nhập thành công", "Thông báo")
            Dim form2 As New frmDanhsach()
            form2.ShowDialog()
            Me.Close()
        ElseIf txtTaikhoan.Text = "" Or txtMatkhau.Text = "" Then
            MessageBox.Show("Tài khoản và mật khẩu không được để trống", "Thông báo")
        Else
            MessageBox.Show("Sai tài khoản hoặc mật khẩu", "Thông báo")
        End If
    End Sub

    Private Sub btnThoat_Click(sender As Object, e As EventArgs) Handles btnThoat.Click
        Dim result As DialogResult = MessageBox.Show("Bạn có chắc chắn muốn thoát chương trình?", "Thông báo", MessageBoxButtons.YesNo)
        If result = DialogResult.Yes Then
            Application.Exit()
        Else
            Me.Focus()
        End If
    End Sub

    Private Sub txtTaikhoan_TextChanged(sender As Object, e As EventArgs) Handles txtTaikhoan.TextChanged

    End Sub
End Class
