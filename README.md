## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_kubernetes"></a> [kubernetes](#provider\_kubernetes) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [kubernetes_deployment.example](https://registry.terraform.io/providers/hashicorp/kubernetes/latest/docs/resources/deployment) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_image"></a> [image](#input\_image) | The image to use for the Kubernetes deployment. | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_deployment_generation"></a> [deployment\_generation](#output\_deployment\_generation) | The generation of the Deployment. |
| <a name="output_deployment_name"></a> [deployment\_name](#output\_deployment\_name) | The name of the Deployment. |
