[ErrorViewModel.txt](https://github.com/user-attachments/files/22516375/ErrorViewModel.txt)
namespace TvcDay05Model.Models
{
    public class ErrorViewModel
    {
        public string? RequestId { get; set; }

        public bool ShowRequestId => !string.IsNullOrEmpty(RequestId);
    }
}
